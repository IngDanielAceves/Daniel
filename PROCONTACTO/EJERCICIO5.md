### Objetos SalesForce

------

![ObManager](https://user-images.githubusercontent.com/91232190/166179024-7e8b573b-7553-47ae-ae4e-0985e6e15fbd.PNG)

------

| Num | Object   | Data | Relationship |
| ------------ | ------------ |------------ |------------ |
| 1 | Lead          | Este objeto tiene como caracteristica guardar los datos de las personas que deseas como clientes. | none |
| 2 | Account       | Estobjeto tiene la caracteristica de guardar datos de una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios).| 4 , 8 , 9|
| 3 | Contact       | En este objeto podemos encontrar los datos de la persona, empresa o dependencia guardada que a la ves esta asociada con Account.| 2 , 8 , 9 |
| 4 | Opportunity   | Este objeto tiene la caracteristica de guardar datos para la administracion sobre una venta o trato pendiente tambien se puede sincronizar este objeto con una cotizacion. | 3 , 6 , 10 |
| 5 | Product       | Este objeto tiene la caracteristica de guardar los datos de varios campos que se usan solo para programaciones de cantidad e ingresos.| 2 , 9 |
| 6  | PriceBook    | Este objeto guarda los datos de precios que contiene la lista de productos que vende su organizacion.| 5 , 4 , 10|
| 7 | Quote         | Este objeto en particular que representa una cotizacion que contiene los datos de registro de precios propuestos para productos y servicios.| 5 |
| 8  | Assest       | Este objeto tiene la caracterisitica de guardar los datos para realizar un seguimiento de los productos vendidos a los clientes.| 2 , 3 , 5 , 9 |
| 9  | Case         | En este objeto guarda datos particularmente los asuntos o problemas del cliente. | 2 , 3 , 5 , 8 |
| 10  | Article     | Este objeto se puede utilizar para asociar un artículo con categorías de datos de un grupo de categorías de datos o para consultar las selecciones de categoría de un artículo. | none |

-----

### Diagrama UML Drawio

-----

![DiagramaxmlObjects](https://user-images.githubusercontent.com/91232190/166179663-520b4c46-f931-4baa-97f6-2dffed5396ac.PNG)

-----

[DIAGRAMA EN DRAWIO LINK](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.drawio#R7Vzfc6o4FP5rfLRD%2BKU%2BVlvvzk53tzud2du7LzsRUs0UiBfiVe9fvwEShAOCtYoOV18Kh5MEcr4vfDkJ7RkTf%2FMlxMvFH8wlXk%2FX3E3PeOjpOrJ1JP7Elm1qGep2apiH1JVOO8ML%2FUmkUZPWFXVJVHDkjHmcLotGhwUBcXjBhsOQrYtub8wrtrrEc1IyvDjYK1u%2FUpcv5FNY2s7%2BG6HzhWoZafLKDDvv85CtAtlewAKSXvGxqka6RgvssnXOZDz2jEnIGE%2BP%2FM2EeHG3qh5Ly033XM1uOSQBP6jAADszbA3MIbGMkT3ryxp%2BYG8lu%2BEtxL68%2FYhvVeeIG1%2FGhyvfmyYOxni9oJy8LLET29cCE8K24L4nzpA4TDqExO1q4ix78PjEYT515LGHZ8QbZz04YR4LxaWkD0UxHrL3LBxxtW8s4FPsUy9G2T8kdHGApVlCCsXVYo%2FOA3HiiI4hosJxuafUo5OQk03OJHvuC2E%2B4eFWuMirfVNGcZ2Dh4rsIgcNcyCNWEJyntW1i404kOE5MFSqpVysnhh2y6FaU9%2FDSfflwpF0kHRKYrCgnvuEt2wV33TERQTU2XjBQvpT%2BGNVWFwOVfcKVovaqOeBUO0KvcSVyWZCEoliz6rbUWZ6whHP4OB5eBnRWXJzsYuPwzkNxoxz5isAyaea5lru6cZb8usk3BSI1HBaBh%2Byq8A3%2FDz2LFdHI2vmDjUXvyGE%2BrpZghlxxegpT1nIF2zOAuw97qwgJDksujhaJHZ0QEQE8uKYy1pI4N7HY33c6JIEqaV4PR%2BXA8NHNpS%2FqhrE8Td5b%2FHxwyZ34WGbtSO69FW5xSdxGe3OUqe7YsmZKrcXFxFbhY7sWjz9Tv8NMF1Pn16%2F%2Fvnf5Dv6Xevr8pUoqEF4jR8yUsc4PrUwC4mHOf1RfPtVoSYpKnodb3MOS0YDHuVqfo4NO%2FRaRhG%2BSB8W30xN%2FgOt1t%2FUPuevmyZgRPqE1aUNu1jaQGCET8MnS9Xchj0Ct22DitL4lipKGJsF70gSD05J4irOpPi%2FSnpfC42Vsm2isXkVLM7eOgqumlkL75L%2F8CMsQ%2BCVp0MddSjLDEB2w7DOxbK6IOeU2r3jCPjzm1i7XrFWUmYVBN8r1iDi2lRrdXIhD8EoIjcAdhWAlnVlADRLAPxruRQaYxVQvr3BsKMwRGiPvs3hcFQBQ%2BsEGZNKGI5KMHwOqVBoujZm7P2Gw47iEMwmM3zlU3dtjoaKFre5V3nulZtufctfq517gYlRERt1I0HjzGt0iYkWyC%2F0G7IZ0N1sSn7UuTfMyoalW7vTcj8EuuLQOVqWz5b1ju5Gud9waLc7YytP2cqE3RFk5rF4lE45BI072iBAM9SrWSJRpEYlUh%2FCoWPyF7UcOnVCQ6%2BmVZU%2B%2FRjVymg3YRLi2GQdzDHCis4NSqMEykksEpzbNK6rugWu%2BmQrx3meaG0KaJm37%2BzST8sqRHH6wHWc1nWIVXzZ2%2FXCAiQdgHuDsIBtjfTjhmkgJAyg4c89SP8iS6N3upIiH1gdPT2pTr5cal2CZtaeZcC9PLNr%2FZtWLwFDkHGkIIIVZdRri2tWWRDhqGK30k0NdUINWeja1BCyf5HR%2FpjB%2FkJD%2FaEz0MsM9QbIn%2Bhaw1APMa99aKiH22jMY4d6mEGF74xzD%2FUdn3ZUJHuOoRlqkWYHz1wuwjOY9dGbNoTV%2BzfxDAo4OOs4lGcWlFRt86xqgYy5q1uOqbOqyrauTVVln0d0dLBvO8d06FIXushaVx8onLOuXpUaGx0piK5rvSp7a3eUMZ%2BahxRZ1qZEsq6aeDCLpNI5%2ByA%2FgNto9Y8wD%2B5IMxCgzHE8hDvoG6o9Nw%2F1knz6e8X4LSXVWfEE5sXZdyUNG9zOt9G3vNHyPuTU8W4Y7CoGESqunKEyBFvd3HbaD4uuT4ycfTWrefOMfgm9MIArq0270gZWnX%2BDXoCtHf31zwBkXI2TfWMnTnff6qfuu%2F%2BFYDz%2BDw%3D%3D)

