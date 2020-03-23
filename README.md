# Modeling-Simulation

This is a simulation for fixed bed reactor of Oxidative dehydration ethane to ethylene by Matlab.

## Chemical process description

   Ethylene is usually produced by steam cracking of saturated hydrocarbons and is produced in recent developments by the cracking of catalytic fluidized bed and catalytic dehydrogenation of ethane,
although these processes require high reaction temperatures as well as problems with coke formation and uncontrollable side reactions. Now, the oxidative dehydrogenation technology has two major advantages:
1. Low Energy comsumption
2. Less COx sides produced and coke formation

But two of the leading challenges of this technology can be mentioned below:
1. Development of suitable catalyst capable of lower selectively ethane to produce ethylene at low temperature
2. Desgin of industrial reactor

### Oxidative dehydration reactions
![ODH Reactions](/Rxns.JPG)

Solve systems of time variante PDEs:
Space domain | Time domain
------------ | -------------
  t variable | r ,z variables
ODE Runge-Kutta | Orthogonal Collocation 

### Gas Mass Balance
![Gas](/GasMass.JPG)

### Gas Energy Balance
![Gas](/GasEnergy.JPG)

### Solid Mass Balance
![Gas](/SolidMass.JPG)

### Solid Energy Balance
![Gas](/SolidEnergy.JPG)
