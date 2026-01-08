# Exercise 2 — Cyclomatic Complexity on a Key Method  
_Repo 1: jay-bank_

## Objective  
Analyser la complexité cyclomatique d’une méthode non triviale dans `BankAccount` (ex: `deposit`, `withdraw`, etc.).

---

## Selected Method

- **Method name:**  
- **Cyclomatic Complexity (from CK Metrics):**  
- **WMC (Weighted Methods per Class):**  

---

## 📝 Decision Points (to annotate in the Java file)

Dans le fichier `BankAccount.java`, ajouter des commentaires `// decision point` sur chaque :

- `if`
- `else if`
- `else`
- `switch`
- `case`
- `for`
- `while`
- `do`
- `catch`
- toute autre structure de branchement

👉 **Copie ici les extraits de code annotés ou une liste des lignes concernées :**

```java
// Exemple (à remplacer par ton code réel)
public void withdraw(double amount) {
    if (amount <= 0) { // decision point
        ...
    }
    if (balance >= amount) { // decision point
        ...
    } else { // decision point
        ...
    }
}
