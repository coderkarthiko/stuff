##### Kepler's laws

<br>

##### Law #1: law of elliptical orbits i.e., $F_g\propto \frac{1}{r^2}\implies$elliptical orbits

I'm too lazy to write the proof here. This video - https://www.youtube.com/watch?v=xdIjYBtnvZU&vl=en - by 3Blue1Brown is excellent. Feynman gives an eloquent explanation of why the inverse square nature of gravitation leads to orbits being elliptical. 

<br>

##### Law #2: equal areas are swept in equal times i.e., $\frac{dA}{dt}=$ constant

Angular momentum $\overrightarrow{L}$ is conserved and is same throughout the orbit. Let $\overrightarrow{r}=$ position vector, $\hat{r}=$ unit position vector, $\hat{r_{\perp}}=$ unit vector $\perp$ to $\overrightarrow{r}$ and on elliptic plane, $\hat{r_u}=$ unit vector $\perp$ to $r$ and $\hat{r_{\perp}}$ i.e., unit vector $\perp$ to elliptic plane, $\overrightarrow{v_r}=$ velocity component along $r$, $\overrightarrow{v_{\perp}}=$ velocity component along $\hat{r_{\perp}}$ and $\overrightarrow{v}=\overrightarrow{v_r}+\overrightarrow{v_{\perp}}=$ tangential component of velocity,

$\overrightarrow{L}=m\;\overrightarrow{v}\times \overrightarrow{r}=m\;(\overrightarrow{v_r}\;+\;\overrightarrow{v_{\perp}})\times\overrightarrow{r}=m\;\overrightarrow{v_{\perp}}\times \overrightarrow{r}=m\;v_{\perp}\;r\;\hat{r_u}=L\;\hat{r_u}\implies r\;v_{\perp}=\frac{L}{m}$, (1)

$dA=|\frac{1}{2}\;\overrightarrow{r}\times d\overrightarrow{r}|=|\frac{1}{2}\;r\;\hat{r}\times r\;d\theta\;\hat{r}_{\perp}|=|\frac{1}{2}\;r^2\;d\theta\;\hat{r_u}|=\frac{1}{2}\;r^2\;d\theta \;|\hat{r_u}|=\frac{1}{2}\;r^2\;d\theta$,

differentiating LHS and RHS and using (1),

$\frac{dA}{dt}=\frac{1}{2}\;r^2\;\frac{d\theta}{dt}=\frac{1}{2}\;r^2\;\omega=\frac{1}{2}\;r\;v_{\perp}=\frac{L}{2m}=$ constant$\implies$equal areas are swept in equal times $\blacksquare$

<br>

##### Law #3: square of time period $\propto$ cube of semi-major axis i.e., $T\propto a^{\frac{3}{2}}$

Consider the equation of an ellipse in polar coordinates,

$r(\theta)=\frac{a\;\sqrt{1\;-\;e^2}}{\sqrt{1\;-\;e^2\;cos^2(\theta)}}$,

where $a$ is the semi-major axis and $e$ is the eccentricity. Now shift the ellipse $c=ae$ units to the right so the left focus is at the origin. This new ellipse represents an orbit (in polar coordinates) where the attractor (say, the Sun) is at the focus which is at the origin and the equation for this is derived as follows.

<br>

![[triangle.png]]

<br>

The base of the above triangle is the line joining the focii of some elliptical orbit. By the cosine rule, it's easy to see that all points on this ellipse obey the relation,

$r(\theta)^2+4\;a^2\;e^2-4\;a\;e\;r(\theta)\;cos(\theta)=(2\;a-r(\theta))^2$,

which on further simplification gives, 

$r(\theta)=\frac{a\;(e^2\;-\;1)}{e\;cos(\theta)\;-\;1}$, ... (1)

which is the orbital ellipse as a function of $\theta$, $a$ and $e$. 

Now, $L=m\;v_p\;r_p$ where $m$ is mass of the orbiting body, $v_p$ is velocity at perihelion and $r_p=a\;(1\;-\;e)$ is distance of perihelion. From [[Vis-viva equation]],

$v_p=\sqrt{\mu\;(\frac{2}{r_p}\;-\;\frac{1}{a})}=\sqrt{\frac{\mu\;(1\;+\;e)}{a\;(1\;-\;e)}}\implies L=m\;\sqrt{\mu\;a\;(1\;-\;e^2)}\implies a\;(e^2-1)=\frac{-L^2}{m^2\;\mu}$, ... (2)$^{\psi}$

From Kepler's law #2, we know $\frac{dA}{dt}=\frac{L}{2m}\implies dA=\frac{L\;dt}{2m}$, and integrating LHS and RHS gives,

$\int dA=\int \frac{L\;dt}{2m}\implies \pi\;a^2\;\sqrt{1\;-\;e^2}=\frac{LT}{2m}\implies T=\frac{2\;m\;\pi\;a^2\;\sqrt{1\;-\;e^2}}{L}$ where $T$ is the time period. 

Squaring LHS and RHS,

$T^2=\frac{4\;\pi^2\;a^4\;(1\;-\;e^2)\;m^2}{L^2}$,

and substituting $\frac{m^2}{L^2}=\frac{1}{\mu\;a\;(1\;-\;e^2)}$ from (2) in $T$ gives $T^2=\frac{4\;\pi\;a^3}{\mu}\implies T\propto a^{\frac{3}{2}} \;\blacksquare$

<br>

$^{\psi}$Substituting (2) in (1) gives,

$r(\theta)=\frac{L^2}{m^2\;\mu\;(1\;-\;e\;cos(\theta))}$, ... (3)

which is the orbital ellipse as a function of $\theta$, $L$, $m$, $\mu$ and $e$ where $\mu$ is the standard gravitational parameter. 








