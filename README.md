# precio-viviendas-lima

Modelo de Machine Learning para predecir el precio de viviendas en Lima Metropolitana.

Este repositorio forma parte del proyecto final del curso **GitHub para Producción en Data Science** del Instituto de Analítica y Negocios.

## Objetivo del proyecto

Construir un repositorio profesional de Data Science usando
cat > README.md << 'EOF'
# precio-viviendas-lima

Modelo de Machine Learning para predecir el precio de viviendas en Lima Metropolitana.

Este repositorio forma parte del proyecto final del curso **GitHub para Producción en Data Science** del Instituto de Analítica y Negocios.

## Objetivo del proyecto

Construir un repositorio profesional de Data Science usando GitHub, GitHub Actions, Pull Requests, releases, herramientas de seguridad y consulta mediante API.

## Tecnologías utilizadas

- Python 3.10+
- pandas
- numpy
- scikit-learn
- pytest
- GitHub Actions
- PyGitHub

## Instalación

```bash
git clone git@github.com:Jordi1023/precio-viviendas-lima.git
cd precio-viviendas-lima
python -m venv .venv
source .venv/Scripts/activate
python -m pip install -r requirements.txt
```

## Ejecutar tests

```bash
python -m pytest tests/ -v
```

## Ejecutar entrenamiento

```bash
python -m scripts.entrenar
```

## Estructura general

```text
src/       Código fuente del proyecto
tests/     Tests automáticos
scripts/   Scripts ejecutables
docs/      Documentación metodológica
outputs/   Resultados generados localmente
.github/   Workflows y configuración de GitHub
```
