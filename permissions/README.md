# Shell, permissions

Scripts Bash sur les permissions, les utilisateurs et les groupes sous Linux.
Testés sur Ubuntu 22.04 LTS.

| Fichier | Description |
|---|---|
| `0-iam_betty` | Bascule l'utilisateur courant sur `betty`. |
| `1-who_am_i` | Affiche le nom d'utilisateur effectif de l'utilisateur courant. |
| `2-groups` | Affiche tous les groupes dont l'utilisateur courant fait partie. |
| `3-new_owner` | Change le propriétaire du fichier `hello` pour `betty`. |
| `4-empty` | Crée un fichier vide nommé `hello`. |
| `5-execute` | Ajoute la permission d'exécution au propriétaire de `hello`. |
| `6-multiple_permissions` | Ajoute l'exécution au propriétaire et au groupe, et la lecture aux autres, sur `hello`. |
| `7-everybody` | Ajoute l'exécution au propriétaire, au groupe et aux autres sur `hello`. |
| `8-James_Bond` | Met `hello` en mode 007 : rien pour le propriétaire et le groupe, tout pour les autres. |
| `9-John_Doe` | Met `hello` en mode 753 (`-rwxr-x-wx`). |
| `10-mirror_permissions` | Copie le mode de `olleh` sur `hello`. |
| `11-directories_permissions` | Ajoute l'exécution à tous les sous-répertoires du répertoire courant, sans toucher aux fichiers réguliers. |
| `12-directory_permissions` | Crée le répertoire `my_dir` avec les permissions 751. |
| `13-change_group` | Change le groupe de `hello` pour `school`. |
| `14-change_owner_and_group` | Change le propriétaire en `vincent` et le groupe en `staff` pour tout le contenu du répertoire courant. |
| `15-symbolic_link_permissions` | Change le propriétaire et le groupe du lien symbolique `_hello` en `vincent` et `staff`. |
| `16-if_only` | Change le propriétaire de `hello` pour `vincent`, uniquement s'il appartient à `guillaume`. |
