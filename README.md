# Modelling the Interplay between Infodemic and Epidemic

## Overview

Anti-vaccine sentiment can be thought of as a culturally transmitted trait that persists in some populations. The spread of anti-vaccine sentiment can be 
modelled by analogy with the SIR model of a transmissable biological pathogen. We thus model the coupled dynamics of anti-vaccine sentiment (cultural pathogen) and
infection by an infectious agent against which a vaccine protects (biological pathogen) using an extended SIR framework. 

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 49 05 PM" src="https://user-images.githubusercontent.com/55981443/144434486-adf282c2-c572-410a-b940-f9d826a0c310.png"> </p>

## Flow Diagram and Equations

The full 13-compartment system comprises the sentiment subsystem and the standard disease subsystem. The disease subsystem comprises five parameters including  1) birth rate b, 2) disease transmission rate β for S → I transitions, 3) disease recovery rate g for I → R transitions, 4) vaccination rate v for Sp → Sv transitions and 5) death rate k for I → D transitions. The sentiment subsystem comprises three parameters corresponding to the intercompartmental transition rate parameters β, g and v in the disease model: sentiment transmission rate c for U → A transitions, anti-vaccine-to-pro-vaccine switching rate s for A → P transitions and pro-vaccine decision rate w for U → P transitions.

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 47 30 PM" src="https://user-images.githubusercontent.com/55981443/144434211-c025da45-b633-4ea4-9732-20f3c136a25c.png"> </p>

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 47 50 PM" src="https://user-images.githubusercontent.com/55981443/144434269-aa2bab8a-6dff-4a4f-a1de-476e3b942e66.png"> </p>

## Effect of Sentiment Parameters on Epidemic

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 52 10 PM" src="https://user-images.githubusercontent.com/55981443/144434946-1b8a9d7f-3dda-4d84-9ab6-f562721bb9f6.png"> </p>

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 52 29 PM" src="https://user-images.githubusercontent.com/55981443/144434999-f798ba84-c344-4191-99bd-de9e66de4eee.png"> </p>

## Deriving Basic Reproduction Number for Disease and Sentiment Subsystem 

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 54 05 PM" src="https://user-images.githubusercontent.com/55981443/144435468-f04a6f64-3d65-4ca4-b668-ffd06e8d0153.png"> </p>

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 54 13 PM" src="https://user-images.githubusercontent.com/55981443/144435477-c4356898-1765-435f-88fe-9402f54ab7cc.png"> </p>

## Policy Recommendations

<p align="center"> <img width="812" alt="Screenshot 2021-12-02 at 9 54 40 PM" src="https://user-images.githubusercontent.com/55981443/144435489-46a2f32b-33fc-46fa-bf21-4a31e1d3c916.png"> </p>

## References

[Modelling Anti-vaccine Setiment as a Cultural Pathogen](https://www.cambridge.org/core/journals/evolutionary-human-sciences/article/modelling-antivaccine-sentiment-as-a-cultural-pathogen/70DEF4B1DB6ED46CBD1E3B18481C24A2)


