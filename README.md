# Notatki z kursu "Wstęp do uczenia głębokiego i sztucznych sieci neuronowych dla inżynierów (Sieci neuronowe PYTORCH)"

## Setup

Aby móc odpalić notatki należy:

1. W powershellu sklonować repositorium. <br>

```
git clone https://github.com/ReptilianEye/PyTorchNotes.git
```

2. Przejść do folderu.

```
cd PyTorchNotes
```

3. Zainstalować [anacondę](https://www.anaconda.com/products/individual) (albo mini-conda)

4. Otworzyć terminal anacondy, wejść do folderu z notatkami i stworzyć środowisko wirtualne z pliku environment.yaml:

```
conda env create -f environment.yaml
```

5. Używać w vscode: (należy wybrać kernel: pytorch_env)

```
code .
```

Jeśli chcesz używać w normalnym notatniku:

1. Aktywować środowisko wirtualne:

```
conda activate pytorch_env
```

2. Odpalić notatki:

```
jupyter notebook
```
