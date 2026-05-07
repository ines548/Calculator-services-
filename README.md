# Calculator Services ROS 2

## 📂 Structure du projet

```bash
Calculator-services-
│── calculator_service/
│   ├── srv/
│   │   └── Calculator.srv
│   ├── calculator_server.py
│   ├── calculator_client.py
│   └── package.xml
│── README.md
```

---

##  Installation

###  Cloner le repository

```bash
git clone https://github.com/ines548/Calculator-services-.git
cd Calculator-services-
```

###  Compiler le workspace

```bash
colcon build
```

###  Sourcer le workspace

```bash
source install/setup.bash
```

---

## Exécution

### Lancer le serveur

```bash
ros2 run calculator_service calculator_server
```

### Lancer le client

Dans un nouveau terminal :

```bash
source install/setup.bash
ros2 run calculator_service calculator_client
```

---

## Exemple de fonctionnement

Entrée :

```bash
Nombre 1 : 10
Nombre 2 : 5
Opération : +
```

Sortie :

```bash
Résultat : 15
```

