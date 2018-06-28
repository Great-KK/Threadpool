# Threadpool
Threadpool

inc includes condition.h threadpool.h
src includes condition.c threadpool.c main.c

gcc -o threadpool condition.c threadpool.c main.c -lpthread -lrt
