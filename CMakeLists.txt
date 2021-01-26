cmake_minimum_required(VERSION 3.17)
project(MonteCarloProjectC++)
set(CMAKE_CXX_STANDARD 14)


add_executable( MonteCarloProjectC++
        Asian.h Asian.cpp BlackScholesModel.cpp BlackScholesModel.h Complex.cpp Complex.h
        Digital.cpp Digital.h European.cpp European.h  main.cpp MonteCarloPricer.cpp MonteCarloPricer.h
        PathDependentOption.cpp PathDependentOption.h PathIndependentOption.cpp PathIndependentOption.h PriceCI.cpp PriceCI.h)