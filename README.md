python-lecture
==============

Wykłady z Pythona na AGH w formacie IPython Notebook.

### Jak używać?

#### Na Linuksie

W celu uruchomienia IPython Notebooka należy:

0. Zainstaluj dodatkowe pakiety systemowe wymagane przy instalacji modułu iPython:
  
  ```
  $ sudo apt-get install libzmq-dev python-zmq python-dev
  ```

1. Zainstaluj pełny moduł iPython:

  ```
  $ pip install ipython[all]
  ```

2. Pobierz źródła:

  ```
  $ git clone https://github.com/agh-glk/python-lecture.git
  ```
  
3. Wejdź do katalogu z wykładem:

  ```
  $ cd python-lecture
  ```

4. (Opcjonalnie) Jeśli chcesz uaktualnić źródła wykładu wykonaj:

  ```
  $ git pull
  ```

5. Uruchom Notebook:

  ```
  $ ipython notebook
  ```
  
Po wykonaniu powyższych czynności w przeglądarce pod adresem `http://localhost:8888/` powinien odpowiadać IPython Notebook.


#### Na Windowsie

W celu uruchomienia IPython Notebooka:

1. Zainstaluj Anacondę: [strona pobierania](http://continuum.io/downloads).

2. Zaktualizuj Anacondę oraz IPythona:

  ```
  conda update conda
  conda update ipython
  ```

3. Pobierz źródła poprzez polecenie w Git Bash (jeśli nie masz Gita, [zainstaluj go](http://git-scm.com/download/win)):

  ```
  $ git clone https://github.com/agh-glk/python-lecture.git
  ```
4. Wejdź do katalogu z wykładem:

  ```
  $ cd python-lecture
  ```
    
5. (Opcjonalnie) Jeśli chcesz uaktualnić źródła wykładu wykonaj:

  ```
  $ git pull
  ```

6. Uruchom Notebook:

  ```
  $ ipython notebook
  ```

Jeśli powyższa komenda nie działa, spróbuj

  ```
  $ ipython notebook nazwa_pliku.ipynb
  ```
  
Po wykonaniu powyższych czynności w przeglądarce pod adresem `http://localhost:8888/` powinien odpowiadać IPython Notebook.



### Poprawki zauważonych błędów

Wszelkie erraty i poprawki mile widziane, proszę zrobić fork + pull request. 
