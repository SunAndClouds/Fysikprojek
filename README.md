# Fysikprojek med forskningsanknytning

## En typiskt simulering för 400 partiklar 
![Particle interactions](https://user-images.githubusercontent.com/80876176/197563306-ac92e79b-72e5-4604-a0cc-e77e7c674892.gif)

Den externa potentialen uppfyller 
$$
\frac{\partial^2V}{\partial x^2} + \frac{\partial^2V}{\partial y^2}= -20
$$
med Dirichlets randvillkor.
Coulomb kraften ges av 
$$
    \mathbf{F}_i = 
    \sum_{j=1}^{N}
    \frac{0.05}
    {\norm{ \mathbf{r}_i - \mathbf{r}_j }^3}
    \mathbf{r}_{ij}.
$$

