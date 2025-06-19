# Instalación

Esta sección describe cómo instalar y desplegar el sistema HLVS.

=== "Python (recomendado)"
    ```bash
    git clone https://github.com/LuisMa565/Taller4.git
    cd Taller4
    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ```

=== "Docker"
    ```bash
    git clone https://github.com/LuisMa565/Taller4.git
    cd Taller4
    docker build -t hlvs .
    docker run -d -p 8000:8000 hlvs
    ```

!!! warning "Requisitos previos"
    Asegúrate de tener Python 3.8+ o Docker instalado antes de continuar. 