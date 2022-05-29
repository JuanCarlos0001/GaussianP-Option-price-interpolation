# GaussianP-Option-price-interpolation

Author: Juan Carlos Ramirez Cano

Date: January 2022

Disclaimer:
This solution is showcased to share my understanding of the problem and my own approach to it.
This solution is not intended for any general application.

Our goal in this project is to be able to hedge an investment portfolio that is highly correlated with the S&P 500 index, for this purpose, we turn our attention to CBOE's S&P 500 European Call Options, which are instruments mainly designed to help investors manage risk in their portfolios. Since our objective is to hedge our portfolio, we want to be able to know the price at which this instruments can be immediately bought in the market even if there are no quotes available for it.
