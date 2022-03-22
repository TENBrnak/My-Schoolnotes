# Střídavý Proud
![[Sketch 16.png]]
### -> střídavý proud mění svoji velikost i směr
zelená = není
červená = je
modrá = je
fialová = není

![[Sketch 17.png]]
${i}$... okamžitá hodnota proudu
${T}$... Perioda
${f}$.... frekvence ${f = \frac{1}{T}}$

${i = I_m * sin(⍵) * t}$

${I_m}$.... amplituda (maximální hodnota)
${⍵}$.... úhlová frekvence
${t}$... čas

${⍵ = \frac{2\pi}{T} = 2\pi f}$

${u = U_m * sin(⍵) * t}$
${u}$... okamžitá hodnota napětí
${U_m}$.... amplituda napětí

![[Sketch 18.png]]
nahoře -> kolík = uzeměn, ochrana při zkratu
vlevo -> fázový vodič = napětí o efektivní hodnotě 230V
vpravo -> nulový vodič = napětí 0V

##### Evropa:
${f = 50 Hz}$
${T = \frac{1}{f} = \frac{1}{50} = 0.02s = 20ms}$

za sekundu změní proud směr 50x
### Efektivní hodnota
= odpovídá hodnotě stejnosměrného proudu, který má v obvodu stejný výkon jako proud střídavý
výkon: ${P = U * I}$
"průměrná hodnota" proudu či napětí = to co měří voltmetr

## Obvody střídavého proudu
### 1.  obvod s rezistorem
![[Sketch 19.png]]
kroužek s vlnovkou = zdroj střídavého napětí
R = elektrický odpor
### 2.  obvod s cívkou
![[Sketch 20.png]]
${L}$ = indukčnost
${⍵}$.... úhlová frekvence
${X_L}$.... zdánlivý odpor cívky = ${X_L = ⍵ * L}$
${[X_L]}$ = ${Ω}$(ohm)
**propouští dobře pomalé frekvence**
### 3. obvod s kondenzátorem
![[Sketch 21.png]]
${X_C}$.... kapacitance = zdánlivý odpor kondenzátoru
${C}$.... kapacita
${X_C = \frac{1}{⍵ * C}}$
${[X_C]}$ = ${Ω}$(ohm)
**propouští dobře rychlé frekvence**
## Jednoduchý RLC obvod v sérii
![[Sketch 22.png]]
rezistor, cívka i kondenzátor mají na sobě napětí
#### Fázorový diagram
![[Sketch 23.png]]
napětí se nedají sčítat = každé jde na jinou stranu 
## Impedance
${Z = \sqrt{R^2 + (X_L - X_C)^2}}$
${Z}$.... impedance 
${[Z] = Ω}$ (ohm)

${tan(μ) = \frac{X_L - X_C}{R}}$



#fyzika #formula 