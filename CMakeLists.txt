cmake_minimum_required(VERSION 3.29)
project(Schnorr_Scheme)

set(CMAKE_CXX_STANDARD 26)

add_executable(Schnorr_Scheme main.cpp
        helpers/math-operations/MathOperations.cpp
        helpers/math-operations/MathOperations.h
        helpers/schnorr-operations/SchnorrOperations.cpp
        helpers/schnorr-operations/SchnorrOperations.h
        helpers/schnorr-verification/SchnorrVerification.cpp
        helpers/schnorr-signature/SchnorrSignature.cpp
)
