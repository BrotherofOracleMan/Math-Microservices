# Math-Microservices
Project for Learning about Go, Microservices, and Docker

Requirements

1) Must Use Go-Kit for setting up microservices
2) Three different containers will be setup. Three microservices: Math equation service, Physics equation service, and Main Service
3) Final deployment will be done via docker containers containers 

Steps

1) Code the physics and math equations first.
2) Piece together each service. 
3) Create Middleware and routing and transport using go kit
4) Combine Code and make sure it works
5) Create individual dockerfile for each service
6) Then use kubernetes or compose to spin up containers.


API Gatway - Electron will communicate with two microservices


Math Microservice

POST QuadraticEquation
POST Pow(x,n)
POST Distance formula
POST Integral
POST Derivative

Results MicroService

GET  lastResult
GET  latestresults
DELETE CLEARALL




