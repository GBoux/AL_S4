# TP n°1:
---
On considère la structure suivante :

```
typedef float E;
typedef struct matrix {
E *mat;
int nb_rows, nb_columns;
} Matrix;

Après avoir implémenter cette structure de matrice en mémoire, Définir les opérations :
- Matrix newMatrix(int nb rows, int nb columns);
- E getElt(Matrix m, int row, int column);
- void setElt(Matrix m, int row, int column, E val);
- void deleteMatrix(Matrix);

• puis les opérations :
- int isSymetric(Matrix); // 0 si faux
- int isSquare(Matrix); // 0 si faux
- Matrix transpose(Matrix);
- Matrix addition(Matrix, Matrix);
- Matrix multiplication(Matrix, Matrix); // NULL si incompatible
- Matrix mult_scalar(E, Matrix);
```
---
