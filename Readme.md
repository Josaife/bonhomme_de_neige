# Projet Bonhomme de neige

Projet RDV Semestre 8 réalisé en binôme avec Mathis Georgel.

## Compilation
```sh
git clone --recurse-submodules https://github.com/Josaife/bonhomme_de_neige.git
cd bonhomme_de_neige
git checkout master
git submodule update --init
mkdir build
cd build
cmake ..  
make
```

### Exécution
```sh
./snowman_raytracing
```
