## lab02 debug
* Run the code that has errors and fix it so that there are no more errors and it works: an app that displays prime numbers

````py
def diviseur(a, b):
    """
    Retourne vrai si b est un diviseur de a
    """
    return b % a == 0

def est_premier(n):
    if n < 2:
        return False
    diviseur_trouve = False
    diviseur_potentiel = 2
    while diviseur_potentiel <= n // 2:
        diviseur_trouve = diviseur(n, diviseur_potentiel)
        diviseur_potentiel = diviseur_potentiel + 1
    return not diviseur_trouve

print("Bienvenue dans l'application qui affiche des nombres premiers")

print("Voici les nombres premiers entre 0 et 29 :")
for i in range(30):
    if est_premier(i):
        print(i)
````

* <details><summary>Answer</summary>True</details>
