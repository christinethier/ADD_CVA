# CVA sensitivities with Algorithm Adjoint Differentation
This repository illustrates the code for my bachelor project, which centers around the implementation of the Adjoint Differentiation Algorithm for calculating Credit Valuation Adjustment (CVA) sensitivities.

The project incorporates the following algorithms:
* Monte Carlo Simulations
* Finite Differentation
* Algorithm Adjoint Differentation

The project aims to address the following question:
How can Algorithmic Adjoint Differentiation be employed to determine selected sensitivities related to Credit Valuation Adjustments for options priced through Monte Carlo simulations within a Black-Scholes framework? How can values for these sensitivities be utilized to analyze individual risks associated with Credit Valuation Adjustments?

Abstract:\\
This paper serves as an introduction to the financial application of Algorithmic Adjoint Dif- ferentiation (AAD) with the objective to compute sensitivities of Credit Valuation Adjustments (CVA) for options. The options in question are priced using various Monte Carlo simulation techniques in a Black Scholes framework. For the type of options for which Monte Carlo simulations are usually applied, these are typically impractical to calculate analytically, and their sensitivities are too time-consuming to evaluate with Finite Difference (FD) techniques. In this paper, we address this problem and show how AAD can be employed to calculate sensitivities efficiently and accurately using operator overloading. Furthermore, the paper confirms that AAD computes sensitivities faster and more exact than traditional FD techniques. We exemplify the basic workings of this computational approach by applying it to simple examples of European options and two types of barrier options, and by operating a simplified model for the calculation of their CVAs. Finally, the sensitivities of CVA for fictional options are calculated and analy- sed for different levels of moneyness, which identified some interesting risk characteristics. The methods described are implemented in Python 3 and all numerical results were obtained using this implementation. As such, the implementation should not be seen as competitive towards implementations in compiled languages, and it should only serve as an introductory demonstration. Several simplifying assumptions have been used when determining CVA. Despite these simplifications, AAD is proving to be a lucrative area of research in the financial world, where accurate and rapid estimation of sensitivities is an increasing priority.
