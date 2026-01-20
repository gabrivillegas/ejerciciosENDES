# Repositorio Remoto

## 1. Verifica Tus Remotos Actuales

Para comenzar, es recomendable verificar los remotos configurados en tu repositorio local para asegurarte de que estén correctos y actualizados.
## Verifica tus remotos actuales
```
git remote -v
```
## Agrega el repositorio original como remoto upstream
```
git remote add upstream https://github.com/profeinformatica101/ejerciciosENDES
```
## Trae las ramas del repositorio original (upstream)
```
git fetch upstream
```
## Crea tu propia rama basada en TDD
```
git checkout -b TDD upstream/TDD
```
## Sube los cambios a tu repositorio
```
git push origin TDD
```
