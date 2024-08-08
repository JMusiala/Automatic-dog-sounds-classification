-PL-

Celem projektu było wykonanie automatycznej klasyfikacji dźwięków wydawanych przez psy, wykorzystując do tego algorytmy uczenia maszynowego.

Projekt zawiera wielowątkowe i kompleksowe podejście do rozwiązania rzeczywistego problemu klasyfikacyjnego dotyczącego rozróżnienia próbek dźwiękowych.
Całość opracowano w języku Python używając wielu popularnych bibliotek upierających się na analizie danych ich przetwarzaniu oraz machine learningu 
w tym m. in.:-Numpy, -Scipy, -Scikit-learn, -Pandas czy -Librosa. 

Skrypt programu opiera się na indywidualnej bazie próbek dźwiękowych trwających od kilku do kilkunastu sekund i zapisanych w formacie .wav. 
Baza dźwięków zawiera łącznie 600 elementów - równo po 100 próbek z każdej z wydzielonych grup psich odgłosów, którymi były:
-szczekanie, -wycie, -skomlenie, -dyszenie, -chrapanie oraz -warczenie.

Pliki dźwiękowe zostały wstępnie znormalizowane, obrobione, a następnie przetworzone do postaci Mel-celspralnych parametrów synału MFCCs.

Następnie przeprowadzono obszerny proces treningu wykorzystując i porównując kilka metod uczenia maszynowego w tym algorytmów lasu lasowego czy Maszyny wektorów nośnych SVN.
Wyniki zostały przeanalizowane, a na końcu przeprowadzono proces optymalizacji modeli uczenia w celu ostatecznej poprawy rezultatów wykorzystując do tego pakiet Optuna.

-ENG-

The main aim of the project was to perform automatic classification of sounds made by dogs, using machine learning algorithms.

The project contains a multithreaded and comprehensive approach to solving a real classification problem concerning the discrimination of sound samples.
The whole project was developed in Python using a number of popular libraries that insist on data analysis, signal processing, and machine learning. 
Including, but not limited to:-Numpy, -Scipy, -Scikit-learn, -Pandas or -Librosa. 

The programme's script is based on an individual database of sound samples lasting from a few to several seconds and saved in .wav format. 
The sound database contains a total of 600 elements - equally 100 samples from each of the separated groups of dog sounds, which were:
-barking, - howling, -screaming, -breathing, -snorting and -screaming.

The sound files were pre-normalised, processed and then transformed into Mel-cepstral parameters of the MFCCs form.

An extensive training process was then carried out using and comparing several machine learning methods including Random Forest Algorithms or SVN Support Vector Machines.
The results were analysed and finally a process of optimising the learning models was carried out to ultimately improve the results using the Optuna package.


