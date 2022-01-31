Zwykły program "Hello Word" z użyciem OpenMP. Kompiluje się za pomocą komendy g++ laby13.cpp -o laby13.exe -fopenmp a uruchamia ./laby13.exe. 
Jednak przed uruchomieniem należy ustawić liczbę wątków na 4 za pomocą export OMP_NUM_THREADS=4. Biblioteka, która zapewnia nam działanie OpenMP jest 
deklarowana za pomocą #include <omp.h>. Identyfikator numeru wątku uzyskujemy dzięki omp_get_thread_num(). Wynik działania programu jest przedstawiony na zdjęciu.
