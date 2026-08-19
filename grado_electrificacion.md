# Actividad

![Plano](images/plano001.png)

2026-08-12

## 5 Demanda de Potencia Máxima Simultánea (DPMS)

| Circuitos | Norma | N° bocas | Potencia (VA) |
|-----------|-------|----------|---------------|
| IUG | 0.66 * c. b. * 150 | 8 | 792 va |
| TUG | 2200 VA | 1 | 2200 va |
| **DPMS** | | | 2992 va |

## 6 Verificación Grado Electrificación

| Grado | Sup | Pot |
|-----------|-------|
| Minimo | 60m<sup>2</sup> | 3,7 kva |
| Minimo | 60m<sup>2</sup> | 2,992 kva |

## 7 Verificación corriente del proyecto.

|Circuitos|Potencia (VA)|Tensión (V)|Corriente (A)|
|--|--|--|--|
| IUG | 792 VA | 220 V | 3,6 A |
| TUG | 2200 VA | 220v | 10 A |
| DPMS | 2992 VA | 220 V | 13,6 A |

S = V*I

I = S / V

## 8 Sección

|Circuitos|Corriente (A)|Sección mm<sup>2</sup>|
|-|-|-|
| IUG | 3,6 | 1,5 |
| TUG | 10 | 2,5 |
| DPMS | 13,6 | 4 |

<hr>
2026-08-19

## 9 Interruptor termomagnético

|Circuitos|Corriente (A)|Termomagnética|
|-|-|-|
| IUG | 3,6 | 6 |
| TUG | 10 | 16 |
| DPMS | 13,6 | 20 |

I<sub>proyecto</sub> &le; I<sub>interruptor</sub> &le; I<sub>conductor</sub>

|I<sub>proyecto</sub>|&le;|I<sub>interruptor</sub>|&le;|I<sub>conductor</sub>|
|-|-|-|-|-|
|3,6| |6| |15|
|10||16||21|
|13,6||20||28|

## 10 Verificar protección de sobrecargas

1. I<sub>f</sub> < 1,45 &times; I<sub>c</sub>

2. 1,45 &times; I<sub>n</sub> < 1,45 &times; I<sub>c</sub>

|Circuitos|Corriente (A)|Termomagnética|Por tabla (A)|1,45 &times; I<sub>c</sub>|
|-|-|-|-|-|
| IUG | 3,6 | 6 |15|21,75|
| TUG | 10 | 16 |21|30,45|
| DPMS | 13,6 | 20 |28|40,6|

## 11 Verificar caída de tensión

&Delta;U = (2.L.I.ro)/S

<math display="block">
	<mrow>
		<mi>x</mi>
		<mo>=</mo>
		<mfrac>
			<mrow>
				<mn>2</mn>
				<mo>L</mo>
				<mi>I</mi>
				<mo>&ro;</mo>
			</mrow>
		</mfrac>
	</mro>
</math>

|Circuito|L<sub>m</sub>|%u|Max %|
|-|-|-|-|
|IUG|20|0,76|3%|
|TUG|36|2,29|5%|

&Delta;u=(2.20.3,6.0,0175)/1,5

&Delta;u=1,68v

%u=(&Delta;u/V).100

%u=(1,68/220).100

%u=0,76