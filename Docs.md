```# git init```

This command creates an empty Git repository on your local machine. So, basically a ```.git``` directory.

---

```## Important Flags```

- ```--bare``` Create a bare repository. If GIT_DIR environment is not set, it is set to the current working directory.

---

- ```--shared[=(false|true|umask|group|all|world|everybody|<perm>)]``` Specify that the Git repository is to be shared amongst several users. This allows users belonging to the same group to push into that repository. When specified, the config variable "core.sharedRepository" is set so that files and directories under $GIT_DIR are created with the requested permissions. When not specified, Git will use permissions reported by umask(2).

---