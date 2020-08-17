# talleragosto2020

Repositorio de taller de linux 

## Requerimientos 
Tener previamente instalado Ansible

## Installation
Para clonar el repositorio y obtener los playbooks.


```bash
git clone https://github.com/augusto-estefan/talleragosto2020
```

Para que funcione correctamente se tiene que editar el archivo playbooks/roles/httpd/vars/main.yml
## Usage

```python
---
# vars file for httpd
member01: 'http://IPNODO1:8080'
member02: 'http://IPNODO2:8081'
mycluster: 'CLUSTERNAME'
```
Esto se debe editar segun las ip y el nombre de cluster del ambiente.

## Contributing
AEMRLP Company®

## License
[MIT](https://choosealicense.com/licenses/mit/)
