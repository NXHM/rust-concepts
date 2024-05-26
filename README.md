# Practicando RUST
Estoy aprendiendo los conceptos de Rust en este repositorio 

En este repositorio estarán algunos ejemplos de la documentación de Rust con su explicación en comentarios

## Correr código para desarrollo
Lo estoy corriendo en Ubuntu 22.04 (25-5-24) en Windows System Linux
### 2 Pasos
1. Primero se compila en el proyecto
```shell
cargo build
```
2. Se ejecuta colocando el path del compilado
```shell
./target/debug/<nombre-compilado>
```
### 1 Paso
1. Compila y ejecuta
```shell
cargo run
```
## Revisar código
Revisa si el código es correcto para compilar (ahorra tiempo al no intentar compilar)
```shell
cargo check
```
## Correr código para despliegue
Se le realizan optimizaciones
```shell
cargo build --release
```