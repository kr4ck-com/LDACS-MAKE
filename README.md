# Proof of Security of the Mutual Authentication and Key Exchange Procedure in the L-band Digital Aeronautical Communication System

The contribution of this paper is the formal proof of the security of this protocol. Using the symbolic model checker Tamarin, we could build a mathematical, formal model of the LDACS MAKE procedure and following several security objectives that this procedure must fulfill, we derived several provable lemmata for Tamarin. Tamarin finally proved that the LDACS MAKE procedure is secure in the standard model and is proven to have no design flaws in its architecture.
This constitutes an important step for the development of the general LDACS cybersecurity architecture since authentication and key establishment are the most crucial steps in establishing secure wireless communication.

## Authors: 

Dobleblind - TBA

## **Paper**

- Conference details for publication

## **File structure:**

- `ldacs_make.spthy`

  - contains a formal analysis of the proposed mutual authentication and key agreement protocols of LDACS and to prove their security.
  
- `tamarin.png`

  - contains a graphical output of the proof of MAKE protocol 
  

## The Tamarin prover repository

For installation and usage instructions of the Tamarin prover see chapter 2 of the manual:

https://tamarin-prover.github.io/manual/book/002_installation.html

## Build environment

Tamarin prover: v1.6.0

OS: Linux based Ubuntu 18.04 Laptop

Configuration: Intel(R) Core(TM) i7-8650U CPU 16GB of RAM

Verification time: 36.159s  

