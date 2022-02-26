# Locust

<https://docs.locust.io/en/stable/quickstart.html#locust-s-web-interface>


### Inicializar

```
sudo apt install virtualenv
virtualenv --python=python3.8 venv
source venv/bin/activate
pip3 install locust
```

Executar:

```
locust
```
Visualizar:

<http://0.0.0.0:8089/>


ou executar:
```
locust --headless --users 100 --spawn-rate 1 -H http://localhost:6002
```
