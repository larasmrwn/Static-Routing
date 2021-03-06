## TechStack
ENSP

## General Info
Repo ini merupakan tugas dari mata kuliah Computer Network Management di semester 6. Materi yang diujikan adalah melakukan konfigurasi static routing. Goals dari tugas ini adalah PC A dan PC B dapat saling ping satu sama lain.

## Topologi

- Topologi ini terdiri dari 2 PC (A dan B), 4 router (R1, R2, R3, dan R4), dan interface pada router 2 dan router 4 di-bundling dengan etherchannel. 
- Arah pengiriman paket dari A ke B yaitu R1 > R4 > R2 (active) dan R1 > R3 > R2 (standby)
- Arah pengiriman paket dari B ke A yaitu R2 > R4 > R1 (standby) dan R2 > R3 > R1 (active)

![Topologi](https://user-images.githubusercontent.com/71112016/177991882-63c6fc29-41d5-41ef-994b-bb0f3bbc65f0.png)


![PC A](https://user-images.githubusercontent.com/71112016/177995813-14a8ed4b-b05d-4f13-87b5-3df4155a5ae6.png)


![PC B](https://user-images.githubusercontent.com/71112016/177995850-b7983753-ee51-4981-b19c-5d4a80b00431.png)
