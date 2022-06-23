# LaTeX Differential Equations Radioactive Decay 
BY:

$$
Enrique\ Ulises\ Báez\ Gómez\ Tagle,\ Luis\ Daniel\ Flores\ Cordero,\ Christofer\ Muniz\ Martinez
$$

Using:

$$
Overleaf,\ Texmaker,\ Bruot tex2img,\ HostMath
$$



It is very similar to the “Malthus Model”.

If we look at an initial amount of radioactive material, over time, there is a change in the amount of matter.

Change in the internal configuration of atoms (they are no longer radioactive).

$Rate \ of \ change ∝ quantity → Matter\ M $
$$\frac{d}{dt}M(t) ∝ M(t)$$

## Malthus model
### In general terms:
$$
P'(t) = kP(t) 
\Longrightarrow 
P(t) = P_0e^{kt}
$$

### Using Differential Equations:
$$
\dfrac{dP}{dt} = kP \rightarrow \dfrac{dP}{P} = k \hspace{0.1cm} dt
$$

### Integrating:
$$
\int \frac{dP}{P} = \int k \hspace{0.1cm} dt 
$$

$$
\rightarrow lnP = kt + C_1 
$$ 

$$
\rightarrow P = e^{kt+c_1}
$$

$$
e^{kt}e^{c_1} = e^{kt}C_2
$$

$$
\therefore P(t) = Ce^{kt}
$$

### Substituting C according to the initial conditions
$$ 
P(0) = P_0 = Ce^{0k} = C 
$$

$$ 
\Longrightarrow C = P_0 
$$

$$ 
\therefore P(t) = P_0e^{kt} 
$$

## In radioactive decay (always using the leftover amount)
$$
M(t) = M_0e^{kt} 
$$


## Example:

If 5% of a radioactive substance decays in 50 years:

What percentage will there be at the end of 500 years?

b) And after 1,000 years?

c) What is the half-life of this substance?

$$
1)\ M(50) = 95/100 \ M_0 \longrightarrow M(50) = 0.95M_0
$$

$$
2) \ M_0e^{50k} = 0.95M_0
$$

$$
3) \ k=\frac{ln(0.95)}{50} = -0.001026 \Longrightarrow
M(t) := M_0e^{-0.001026t}
$$

$$ 4.A) \
M(500) = M_0e^{(-0.001026)(500)}
$$

$$
\frac{M(500)}{M_0}=e^{(-0.001026)(500)}
$$

$$
e^{-0.513} = 0.5987 = 59.9/100
$$

$$ 5.B) \
\frac{M(1000)}{M_0}=e^{(-0.001026)(1000)}
$$

$$
e^{-1.026} = 0.3584 = 35.8/100
$$

$$
6.C) \ M(t_m) = 1/2 \ M_0 \longrightarrow M_0e^{kt_m} = 1/2 \ M_o \Longrightarrow e^{kt_m} = 1/2
$$

$$
kt_m = ln\frac{1}{2} \Longrightarrow t_m = \frac{-ln2}{k}  \Longrightarrow  t_m = \frac{-ln2}{-0.001026}
$$

$$
675.582 = 675 \ años, 212 \ días
$$

## Retrieving...
$$
k = -\frac{ln2}{t_m}
$$

$$
M(t) = M_0e^{-\frac{tln2}{t_m}}
$$

## Exercise 1
1) If the amount of C14 contained in a skull is one sixth of the amount at death, what is the age of the skull?

(Radiocarbon dating)

$$
M(t) = 1/6 \hspace{0.1cm} M_0
$$

$$
M_0e^{-\frac{tln2}{t_m}} = 1/6 \hspace{0.1cm} M_0
$$

$$
e^{-\frac{tln2}{t_m}} = 1/6 \hspace{0.1cm}
$$

$$
{-\frac{tln2}{t_m}} = ln(1/6)
$$

$$
{-\frac{tln2}{5730}} = ln1-ln6
$$

$$
-tln2 = -ln6 \hspace{0.1cm}(5730)
$$

$$
t = \frac{-ln6 \hspace{0.1cm}(5730)}{-ln2}
$$

$$
t = 14811.84 \hspace{0.1cm}anios
$$

## Exercise 2
2) The radioactive isotope of lead, Pb-209, decays at a rate proportional to the amount
present at time t and has a half-life of 3.3 hours. If at the beginning there was 1 gram of
lead, how long must it take for it to decay to 90%?

$$
Half-Life= \frac{M_o}{2} = 3.3
$$

$$
\frac{M_0}{2} = M_0e^{3.3k}
$$

$$
\frac{1}{2} = e^{3.3k}
$$

$$
k = -\frac{ln2}{t_m} \Longrightarrow k = -\frac{ln2}{3.3} \Longrightarrow k=-0.21
$$

$$
0.1 = e^{-0.21t}
$$

$$
ln(0.1)=-0.21t
$$

$$
\frac{ln(0.1)}{-0.21} = t
$$

$$
\ t = 10.96 \hspace{0.1cm}horas
$$
