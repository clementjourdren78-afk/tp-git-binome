# tp-git-binome

TP git

## Règles du binôme

1. On commence la journée par un `git pull`, et le café. Dans cet ordre.
2. Un message de commit de moins de 65 caractères. "fix" ne compte pas, "modif" non plus.
3. Personne ne pousse sur `main` après 23h. Les commits de 23h30 s'appellent "test" et "test2".
4. Celui qui commit `Rplots.pdf` (8 Mo) offre les croissants.
5. `git push --force` est interdit. On n'est pas des animaux.
6. Les fins de ligne CRLF ne se discutent pas. Elles arrivent, c'est tout.

## État du projet

| Fichier | Contenu | Commentaire |
| --- | --- | --- |
| `README.md` | ce fichier | passé de 2 lignes à beaucoup plus, sans conflit |
| `notes_A.txt` | rien | Clément réfléchit encore |
| `notes_B.txt` | beaucoup | Pierre a réfléchi à sa place |

## Que faire si

- **Vim s'ouvre** : `:wq`, Entrée, respirer.
- **detached HEAD** : `git switch -`. Vous regardiez juste le passé, pas de panique.
- **CONFLICT** : c'est normal et fréquent. Comme les réunions.
- **Je ne sais plus où j'en suis** : `git status`. Puis `git log --oneline --graph --all`. Puis un croissant.
