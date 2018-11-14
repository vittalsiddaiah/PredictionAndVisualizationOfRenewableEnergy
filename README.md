## Analysis and Visualization of Renewable Energy

[Live Demo](https://vittalsiddaiah.github.io/AnalysisAndVisualizationOfRenewableEnergy/)

--------


In the world today, there is an increasing demand of up to 5% of energy required. Whereas fossil-fuel-reserves covering that need is depleting much faster than the expected. 
Ever since the advent of fossil fuel over a century, automobiles have been increasing and hence the increase in carbon levels in the atmosphere due to the automobiles.
With the growing adverse impacts of fossil fuels on the environment, there is an increasing demand of using renewable energy sources. Most commonly used energy sources are wind and solar energy.
In our research, we analyze wind and solar energy.  The primary parameter for wind energy is wind speed, hence accurate evaluation of wind speed energy is critical.  Most popularly used Weibull PDF (Probably Density Function) is not statistically accepted. Similarly for solar panels sunlight and temperature is very important.  This is an attempt to analyze the renewable energy.


--------


[Live Demo](https://vittalsiddaiah.github.io/AnalysisAndVisualizationOfRenewableEnergy/)

-----

# Power Generated of a Wind Turbine

In 1919, A German physicist Albert Betz concluded that no wind turbine could transform more than 16/27 (59.3%) of the kinetic energy of the wind into mechanical energy turning a rotor. Till date, his postulate is being referred to as the Betz Limit or Betz’ Law.  Regardless of the inefficiencies in the generator, but in the very nature of wind turbines themselves.

The theoretical maximum power efficiency of any design of wind turbine is 0.59 (a wind turbine can generate i.e. no more than 59% of the energy carried by the wind). Once we also factor in the engineering requirements of a wind turbine – strength and durability in particular – the real world limit is well below the Betz Limit with values of 0.35-0.45 common even in the best-designed wind turbines. 0.30-0.35 could be the better considering the wear and tear of the wind turbines over time.

## Deriving the empirical formula

> 1) The power output of a wind generator is proportional to the area swept by the rotor – i.e., double the swept area and the power output will also double.
> 2) The power output of a wind generator is proportional to the cube of the wind speed – i.e. double the wind speed and the power output will increase by a factor of eight (2 x 2 x 2)!

Wind is made up of moving air molecules which have mass – though not a lot. Any moving object with mass carries kinetic energy in an amount which is given by the equation:


```katex
Kinetic Energy = 0.5\ \times\ Mass\ \times\ Velocity^2
```

where the mass measured in kg, the velocity in m/s, and the energy generated in joules.  Air has a known density (around 1.23 kg/m3 at sea level), so the mass of air hitting our wind turbine (which sweeps a known area) each second is given by the following equation:


```katex
Mass/sec\ (kg/s)\ =\ Velocity\ (m/s)\ \times\ Area\ (m^2)\ \times\ Density\ (kg/m^3)
```


Hence the power (i.e. energy per second) in the wind hitting a wind turbine with a certain swept area is given by simply inserting the mass per second calculation into the standard kinetic energy equation given above resulting in the following vital equation:

```katex
Power\ =\ 0.5 \times\ Swept\ Area\ \times\ Air\ Density\ \times\ Velocity^3
```

where Power is given in Watts (i.e. joules/second), the Swept area in square meters, the Air density in kilograms per cubic meter, and the Velocity in meters per second.


```katex
\underline {P_{generated}=\frac{1}{2}\rho Av^3 C_p}

\rho \to Air\ Density  \approx 1.23kg/m^3

A\ is\ the\ area\ = \pi r^2 \approx 8500m^2  
```
Assuming typical length of blade is 52m

```katex
C_p\ \to\ Power Coefficient\ \to\ C_p \lvert _{max}\ =\ 59.3 

v\ =\ Wind-speed\ in\ m/sec

```


