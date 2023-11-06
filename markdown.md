

# "Este es mi primer proyecto en Git"

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)



| Encabezado 1 | Encabezado 2 |
|--------------|--------------|
| Celda 1,1    | Celda 1,2    |
| Celda 2,1    | Celda 2,2    |


1. Primer elemento
2. Segundo elemento
3. Tercer elemento



commit be6d46511105dc1039a3e6b21a5b8319d8add5df (HEAD -> master)
Author: George Pereira <george.pereira.valencia02@gmail.com>
Date:   Mon Oct 30 16:14:22 2023 +0100

    Añadido markdown.md


C:\laboratorio_git>git checkout <ba75dc3>
La sintaxis del comando no es correcta.

C:\laboratorio_git>git checkout ba75dc3
Note: switching to 'ba75dc3'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at ba75dc3 log_dentro


C:\laboratorio_git>git tag v1.0

C:\laboratorio_git>git -d v1.0
unknown option: -d
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

C:\laboratorio_git>git tag -d v1.0
Deleted tag 'v1.0' (was c388d8a)

Cambio klkkkkkkkkkkkkkkkkkkkkkkkkkkkk:\laboratorio_git>git tag v1.0

AHORA SI



C:\laboratorio_git>git diff
diff --git a/markdown.md b/markdown.md
index 064d7a9..202d846 100644
--- a/markdown.md
+++ b/markdown.md
@@ -64,3 +64,5 @@ Deleted tag 'v1.0' (was c388d8a)

 Cambio klkkkkkkkkkkkkkkkkkkkkkkkkkkkk:\laboratorio_git>git tag v1.0

+AHORA SI
+

