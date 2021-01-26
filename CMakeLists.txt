cmake_minimum_required(VERSION 3.17)
project(MonteCarloProjectC++)
set(CMAKE_CXX_STANDARD 14)


add_executable( MonteCarloProjectC++
        Pricer/Asian.h Pricer/Asian.cpp Pricer/BlackScholesModel.cpp Pricer/BlackScholesModel.h Pricer/Complex.cpp Pricer/Complex.h
        Pricer/Digital.cpp Pricer/Digital.h Pricer/European.cpp Pricer/European.h Pricer/main.cpp Pricer/MonteCarloPricer.cpp Pricer/MonteCarloPricer.h
        Pricer/PathDependentOption.cpp Pricer/PathDependentOption.h Pricer/PathIndependentOption.cpp Pricer/PathIndependentOption.h Pricer/PriceCI.cpp Pricer/PriceCI.h)