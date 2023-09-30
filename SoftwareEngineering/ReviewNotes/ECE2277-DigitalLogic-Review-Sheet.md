---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
%%***>>>text element-link:[[ECE 2277]]<<<***%%ECE 2277 ^XJmHOtDA

%%***>>>text element-link:[[General Radix Number Systems]]<<<***%% General Radix 
Number Systems ^9z51tJuw

instead of a "bit"
being 0-9. It is 0-(r-1)
and its decimal value
is:   is the value of bit ^mFV2l8ot

Common Radices ^RuJzyEg4

Converting Bases ^QzuS2g7w

1. Convert to
  Decimal
2. Convert decimal
   Number (n) to 
   base R ^CtYc70tg

divide n by r.
remainder = x0
divide result by r
remainder = x1
repeat until result
= 0 ^VHM11Bj2

Fractional Part: ^RmTIvXhl

decimal * r
whole # = x(-1)
result -   * r
whole # = x(-2)
repeat until 0
or sufficient
accuracy ^ba6NhXMl

Binary Addition ^A45Nq2Ea

same as decimal
addition ^Liq65LGw

Binary Multiplication ^NHOPfgPn

110 * 10 : 110*0 = 0
110 * 1 = 110 ^QVvKMRtI

000 ^ArWxLrz9

110 ^rXZJzQth

+ ^j9p3PGxq

Binary Subtraction ^ELBDs75S

same as normal
subtraction. Or
take complement
of subtracting #
and add them ^m7U2NwBH

%%***>>>text element-link:[[Signed Binary Numbers]]<<<***%%Signed Binary 
  Numbers ^NtRDACja

0 in MSB = +
1 in MSB = - ^xynq8Obp

%%***>>>text element-link:[[Carry Out]]<<<***%%Carry Out ^0Iyvs71R

sum
 ^5kPAwW17

is greater than
availible digits ^xrUVCiRK

%%***>>>text element-link:[[Overflow]]<<<***%%Overflow ^mu0yWaws

sign is ^LkLENFme

changed by
accident ^fSi8XYOW

%%***>>>text element-link:[[Binary Codes]]<<<***%%Binary Codes ^QCiAC70z

each decimal ^GiwONAMM

digit is represented by 4
binary bits. Types:
BCD(8421), 2421, 8,4,-2,-1,
Excess-3 (BCD + 3) ^8yN57yve

Unit 2: Logic ^seKftyGB

%%***>>>text element-link:[[Boolean Algebra]]<<<***%%Boolean Algebra ^pRDkZ99r

AND ^72anB4cq

= OR ^FnasmEY6

NOT ^3IiO0etz

Theorems: ^Ze2rDfwg

1. ^l2ODkkvl

2. ^ofH63O5E

3. ^fkdbqoHZ

4. ^iD8hkXaJ

5. ^nP3u6LIv

6. ^sHCzZFew

Operator Precedence ^CDs6CUWC

Parantheses -> NOT
-> AND -> OR ^OCZcWvGM

%%***>>>text element-link:[[Boolean Functions]]<<<***%%Boolean Functions ^AJd1eFxH

function formed w/
binary variables, 
binary operators, 
Parantheses
(ouput/input 0or1) ^6pPWoABF

2 forms: standard
and canonical ^QBdFWx21

Canonical Function ^9ORaLW8M

(SOP) Sum of
Minterms ^2LVMPvEP

(POS) sum of max
terms ^lnyDwUWg

Standard Function ^RV1oAVFr

(SOP) Sum of 
Products: xy + z'y
(POS) Product of
Sums: (x+y)(z'+y) ^ACQeUnJp

Cost ^uOaPUvT9

sum of:
 ^8t7mUZeJ

# of inputs
Logic Gates
Internal Connecttions ^IObAPv2Z

%%***>>>text element-link:[[Minterms]]<<<***%%Minterms ^DXWrCl6T

x  y  z ^0iuJZz6j

0  0  1 ^pk9VR3wD

what makes
it = 1   name ^4G4lBjO9

m1 ^2cHZcyKA

1  0  1 ^p7abdrqO

m5 ^vwlMdQbC

%%***>>>text element-link:[[Maxterms]]<<<***%%Maxterms ^p0Mh8Uld

same as ^iK1w3I6e

minterms just = 0 and
addition ^uhxod1AG

0 1 1 ^8t9F9wk7

M3 ^81SjDfBB

Unit 3: Minimization ^Z9yR7tsj

%%***>>>text element-link:[[K-Maps]]<<<***%%K-Maps ^6lHMvQPg

to create efficient 
circuits. inputs form
rows & columns. cell
contains output. ^e4ztLcJF

used ^ThVTvkWG

y z ^Db1cGmiY

x ^9JJChVpV

00 ^HcZBJB99

01 ^uMEr2M8K

11 ^3Ru60hEj

10 ^6SnNFnRF

1 ^4rBJnteI

0 ^aKpNj9D2

1 ^8V2HY2hi

1 ^GRIBqRQ3

0 ^ipyoKWZg

1 ^Rfn3LFrd

1 ^XM9mbMfM

1 ^I7SufiKX

x ^ikJw67OU

0 ^wV4Hmoo6

x: dont care. can
be grouped with
1s or 0s
SOP: group all 1s 
into rectangles    in 
size. find consistent
variables. the blocks
add and the 
interiors multiply:   ^ZQFafaG6

(y z) +  ^eRTqzbTs

(x) ^B8XQFpZ5

f = ^YL0Mas9e

POS: same
thing except
as a product
of sums. group
0s ^zzDg1mTJ

y z ^gZjUH0lm

x ^CBrcwQE9

00 ^7IDTTAtF

01 ^aAKqyUXC

11 ^FckO3VMC

10 ^NR3HBpIt

1 ^zL1kOKJZ

0 ^U6goYliR

1 ^HXUU8zYY

1 ^0kBp31Fd

0 ^MtUonATs

1 ^TqpFetPC

1 ^T2CP49Yy

1 ^nEnYpzob

x ^0mKX8ZEN

0 ^Qf1cCcEg

f =  ^rfFF9DjB

(x + z) ^OMcCa0hy

(x + y) ^aZtIoNnd

%%***>>>text element-link:[[NAND]]<<<***%%NAND ^bEt0HVDh

%%***>>>text element-link:[[NOR]]<<<***%%NOR ^iehSN1oo

Unit 4: Combinational Logic ^Z0ruvcFv

a circuit whose output is a
function of only its inputs ^xyT8MfnH

%%***>>>text element-link:[[Decoder]]<<<***%%Decoder ^LJupfP6k

accepts n inputs ^QeaAgw2f

has    outputs. it reads
the binary number then 
outputs a one at one of
the    inputs representing
the decimal for of the #
 ^Fayf9ZGk

%%***>>>text element-link:[[Tri-State Buffer]]<<<***%%Tri-State Buffer ^2PJKWwY6

has 2 inputs & 1 ^PXZsZcue

output. if control(c) input is active 
output = other input. 
otherwise acts as open 
circuit ^OtVkbuK5

%%***>>>text element-link:[[Multiplexors]]<<<***%%Multiplexors ^VPj5WVbH

has ^iGMSXmNR

inputs. output is one of
the    inputs. n is a
binary # to specify which  ^ofoFuz7L

Encoder ^2nue55qj

opposite of a decoder ^yv1ICBma

Half-Adder ^nR9d9OUY

has 2 inputs and 2
 ^xfuMTqLg

outputs. S = sum, C = carry out ^eNy1XN60

x ^A0k6d5lE

y ^nVbnMcJd

S ^RYZ3sn54

C ^49xC6ums

Full Adder ^vhDmkoTp

3 inputs: ^DZ2pMoBT

z = carry out from previous term
rest is the same as Half Adder. ^YyOoZRnj

C ^EBQ4ejwC

S ^4XrSqEpD

x ^3wsdus15

y ^apXgikAw

z ^G1BBzS0W

HA ^2DthqSCe

HA ^EZVBr3dW

FA ^S0BO1r79

x ^P002jook

y ^mmSJcH99

z ^j25NiWr5

C ^L2uLKjoV

S ^orjWLtav

FA ^lqZ3k8tp

x ^EIBroYQD

y ^1LtQ5xXG

z ^dcbWSGHl

C ^tKM9KZC8

S ^RRpEXDsN

2-Bit: ^1Ad9aU1j

a1 ^WOfIYAaj

a2 ^21DfcFuH

b1 ^CK1tqcLy

b2 ^PszQjcph

%%***>>>text element-link:[[Magnitude Comparator]]<<<***%%Magnitude Comparator ^t287YUAS

determines larger binary
magnitude of 2 #s. can
return the larger # or
have 3 ouputs. one for
if equal. one if #1 is
larger. and one if #2
is Larger ^egGUG5gl

Unit 5: Sequential Circuits ^o3drBu1p

%%***>>>text element-link:[[Sequential Circuits]]<<<***%%Sequential Circuits ^wuKSs75i

a circuit that ^5OX6IbMc

depends on inputs and the current
state of the circuit. ^CeULE4u5

%%***>>>text element-link:[[Flip Flops]]<<<***%%Flip Flops ^mAHJEyJy

memory elements usually 
triggered by falling or rising 
edge of a clock (stores new
value when triggered). may have
asynchronous inputs: set means
output = 1. reset means output
= 0. falling edge has a bubble
at the clock input. rising doesnt ^PCOLKeYr

%%***>>>text element-link:[[D Flip Flop]]<<<***%%D Flip Flop ^0FPzYdEQ

has 1 input: D. when ^e6ALVMrc

the flip flop is triggered it stores
value of D ^L9nK2TA1

%%***>>>text element-link:[[T Flip Flop]]<<<***%%T Flip Flop ^AYFOfQUB

has 1 input T. when
 ^MkLIC4OW

T=1 the current value of output
is flipped. When T=0 output holds ^qDamWnq4

%%***>>>text element-link:[[JK Flip Flop]]<<<***%%JK Flip Flop ^fDUAhiBg

2 inputs J & K ^271PFUCY

Set: J=1, K=0. Reset J=0, K=1
Hold: J=K=0. Inverted: J=K=1 ^LHzrFw8F

Unit 6: Counters ^Nj00tnJm

%%***>>>text element-link:[[Counters]]<<<***%%Counters ^LfXWkkJG

a binary counter up to
needs n flip flops ^KmX5TqNa

%%***>>>text element-link:[[Ripple Counters]]<<<***%%Ripple Counters ^BVOFTsME

is an ^gnPO8Mtn

Asynchronous Counter so no
global clock. each flip flop is 
triggered by previous flip flop ^jnuFQk8l

%%***>>>text element-link:[[Synchronous Counter]]<<<***%%Synchronous Counter ^UC75A3hJ

has a ^ImflYyTg

global clock. so all flip flops
are trigged by one clock ^9eBRAltk

Unit 7: Finite State Machines ^n5TSPO5p

%%***>>>text element-link:[[Deterministic FSM]]<<<***%%Deterministic FSM ^6mmrx45V

%%***>>>text element-link:[[Finite State Machine]]<<<***%%Finite State Machines ^68DlqW6w

a system that has ^Io1DWP4s

finite states, inputs, and outputs ^uk6vIJTa

an FSM if every
combination of
state and input
results in only 1
state transition ^AGXZpEnY

%%***>>>text element-link:[[Moore FSM]]<<<***%%Moore FSM ^RowuFtCe

an FSM where the output only ^taSd52Ge

depends on the current state ^TyFJRklW

start ^tWWV7awf

s2 ^6ksUCndo

1 ^Yj4wlmam

s1 ^QBxzeCee

0 ^1OwPlQId

s3 ^Cbjpsg78

1 ^MPhBDEdl

1 ^xgJ2sF1i

1 ^gCc0C1NA

0 ^fS87AeXi

0 ^zZppSuQO

1 ^zbAwhBGz

0 ^5PyjadcF

inputs ^JGJsVhmQ

outputs ^caf1lNKf

states ^fAKhCn1x

%%***>>>text element-link:[[Mealy FSM]]<<<***%%Mealy FSM ^LpTxEDXL

output depends on both input ^XuO2izSN

and current state ^QuDIjCdO

start ^HLzlhrcJ

s2 ^qq3PSzsw

s1 ^OwmCvEJs

s3 ^SmNpGllq

1 ^RuU1phPL

0 ^cFFQOreW

0 ^0dY59pxT

1 ^eVXrTpd9

0 ^rplIqfAF

inputs ^Q9OUxLrU

outputs ^3LQOjLsy

states ^0qj4pMq3

/1 ^epO2D7UP

/0 ^pIxFcrCH

/0 ^Jr6YCmuJ

/0 ^TMFsBune

/1 ^wJL3A0qI

/1 ^I739j6kf

1 ^huN2MRj2

 state
diagram ^WeMFgTpo

 state
diagram ^QJb1Gs4t

state reduction ^MUN1sLf3

find all sets of ^xwIiQGOf

equivalent states: input
sequences: trigger a transition
to the same state or equivalent
state and generate exactly the
same output ^QhngoH0k


# Embedded files
3c5ae178c6153980d9dd2287e74eff290034476a: $$= a_{k-1}\times r^{k-1} +\cdots+ a_{0}\times r^{0}$$
1985430e1e177d04b1c54a506fb11b3c21b8975e: $$a_i$$
92b2405685b042dbf107c00809b08b01297d0bda: $$r=2 \;\; (101)=4+0+1$$
989bf6b1167bd8fcee5d7a934d87a4cae9107455: $$r=8$$
452df7a0813f60fe067e5c98fe049811be72e3d3: $$r=10$$
a5234659e85ec41fc3286e272e51f5b8f68eb3dd: $$r=16$$
5dae4e5c4d8a7919e3ffd7b9aed6fc3b92c1c573: $$x\cdot y = $$
4bf7763a53ba16deac1887eec231422ddc852901: $$x + y$$
f579a537316853914bb0854b3b681ff27e426d34: $$\bar x = $$
72ed837296f4eb2f8d314c7d1a708a79090c3c8a: $$x + x = x$$
16e2744384506a3339e82159ac4dd53c37d5442c: $$x\cdot x = x$$
410a9090df6608f430fabb788d4cd922b02461d6: $$x + 1 = 1$$
ffabaee701a8445a90eee6e5c88abe73ef374714: $$x\cdot 0 = 0$$
e5adb72980aaae9c31cb11c8dc32b5cd22f2f5eb: $$(x')' = x$$
b79d1033bb9586acb49ed5495f8aa2efc1884872: $$x',$$
e5f046b0c9882390696be4612258c2a953a2c3f5: $$x + (y + z) = (x + y) + z$$
06a42b393141efa031aebdce8561c4b076518284: $$x \cdot (y \cdot z) = (x \cdot y) \cdot z$$
7fbce1202ca526e0e24fe2738d6eeeee9bbba898: $$(x + y)' = x'y'$$
9c1100bdf374d59064f8fe149b4e24be2488994d: $$(xy)' = x' + y'$$
9bbb89a9031545a448ee59275a133e9ca008ef4b: $$x + xy = x$$
58722e2b5e8d19b6b1e647212362150fa12cd430: $$x(x+y) = x$$
b4fd9a337a9c3fb868968c50bd4f589a0ad0eb02: $$\bar x\cdot\bar y\cdot z$$
8b0fb5e5dbe9f0787efa239434691a09a7256458: $$x\cdot \bar y \cdot z$$
81dd2f6cddae130a7adc8c4f6ba9a56116eb5943: $$x + \bar y + \bar z$$
e6a4e174f9b400f3cc07024b00c6dd0baf596180: $$2^n$$
75735df3a33b755658e756691d861fb3e53ef328: $$x\uparrow y = \bar x + \bar y$$
8be8ea931a566f2775f17b6e41eb47d5801d8fbb: $$x\downarrow y = \bar x\bar y$$
8e1b854b48d80524c755e9f1196de92b09ec7c03: $$2^n$$
bd7b0c1c3e09ae287d0f56065c1df2be945dd5ce: $$2^n$$
cc011653266071570fc02a7a906c2a8f11f22939: $$2^n + n$$
6530584ce5beeb21985de9a14aea231783a9d7a3: $$2^n$$
e04ce71266f263964899195544b56c22f62ca6c7: $$N = 2^n$$

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://excalidraw.com",
	"elements": [
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1768258785,
			"isDeleted": false,
			"id": "XJmHOtDA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -63.18520595948692,
			"y": -23.09092668204397,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 182,
			"height": 46,
			"seed": 76816,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": "[[ECE 2277]]",
			"locked": false,
			"fontSize": 36,
			"fontFamily": 1,
			"text": "ECE 2277",
			"rawText": "ECE 2277",
			"baseline": 32,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "ECE 2277"
		},
		{
			"type": "rectangle",
			"version": 154,
			"versionNonce": 1734737327,
			"isDeleted": false,
			"id": "m69RlznWWOUSpl1zRde3B",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -77.68213978141006,
			"y": -35.70670874841221,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 206.9231852530234,
			"height": 66.3581020245212,
			"seed": 1366481882,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 266,
			"versionNonce": 675625153,
			"isDeleted": false,
			"id": "SkP9yVXALlI8Vv-Ke7ZWP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 135.31200823017204,
			"y": -22.80700784818663,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 199.24639145833353,
			"height": 54.064699741489164,
			"seed": 798430642,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 262,
			"versionNonce": 1415081935,
			"isDeleted": false,
			"id": "9z51tJuw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 155.64476368949434,
			"y": -19.877393147701127,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 159,
			"height": 50,
			"seed": 45861,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": "[[General Radix Number Systems]]",
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": " General Radix \nNumber Systems",
			"rawText": " General Radix \nNumber Systems",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": " General Radix \nNumber Systems"
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 260208801,
			"isDeleted": false,
			"id": "mFV2l8ot",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 138.27961663049416,
			"y": 33.91949101805616,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 191,
			"height": 80,
			"seed": 1704700398,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "instead of a \"bit\"\nbeing 0-9. It is 0-(r-1)\nand its decimal value\nis:   is the value of bit",
			"rawText": "instead of a \"bit\"\nbeing 0-9. It is 0-(r-1)\nand its decimal value\nis:   is the value of bit",
			"baseline": 75,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "instead of a \"bit\"\nbeing 0-9. It is 0-(r-1)\nand its decimal value\nis:   is the value of bit"
		},
		{
			"type": "image",
			"version": 207,
			"versionNonce": 2054659567,
			"isDeleted": false,
			"id": "gtDhkRy6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 143.30160816259087,
			"y": 115.4338247581808,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 170.58680416141823,
			"height": 14.898410843791986,
			"seed": 46543,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "3c5ae178c6153980d9dd2287e74eff290034476a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 154,
			"versionNonce": 1087159425,
			"isDeleted": false,
			"id": "31dks5vB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 158.43828469134064,
			"y": 99.69305455345798,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15,
			"height": 11,
			"seed": 4192,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1985430e1e177d04b1c54a506fb11b3c21b8975e",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 355,
			"versionNonce": 214697999,
			"isDeleted": false,
			"id": "H1UvrBtSpqPa3m8dFXyB4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 134.68520724808906,
			"y": 31.894802709573113,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 198.58749267101683,
			"height": 102.28005022352319,
			"seed": 1622049518,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 259,
			"versionNonce": 2078508129,
			"isDeleted": false,
			"id": "UP23lu8axRrM_7YQAIdpm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -2.454620371958164,
			"y": 38.22481122518229,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 130.64316397741084,
			"height": 18.824665052892584,
			"seed": 2031368946,
			"groupIds": [
				"7qbWYJrIMts2NYEZ8-jjv",
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1229860399,
			"isDeleted": false,
			"id": "RuJzyEg4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 0.9682123194597168,
			"y": 37.28126435498561,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 125,
			"height": 20,
			"seed": 543753010,
			"groupIds": [
				"7qbWYJrIMts2NYEZ8-jjv",
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Common Radices",
			"rawText": "Common Radices",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Common Radices"
		},
		{
			"type": "image",
			"version": 222,
			"versionNonce": 1553354817,
			"isDeleted": false,
			"id": "yWx1lQgn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -27.643943452157885,
			"y": 66.00252757137055,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 154.3574152493606,
			"height": 14.778901460045164,
			"seed": 20831,
			"groupIds": [
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "92b2405685b042dbf107c00809b08b01297d0bda",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 390,
			"versionNonce": 451317839,
			"isDeleted": false,
			"id": "u3IQEQlm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 36.95015061401792,
			"y": 88.3559231184798,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27.839796057394352,
			"height": 9.506271824476121,
			"seed": 75006,
			"groupIds": [
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "989bf6b1167bd8fcee5d7a934d87a4cae9107455",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 275,
			"versionNonce": 1489281057,
			"isDeleted": false,
			"id": "pXARERpB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -26.52918160132073,
			"y": 87.36810294831531,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.13481458723444,
			"height": 10.117748084425642,
			"seed": 90173,
			"groupIds": [
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "452df7a0813f60fe067e5c98fe049811be72e3d3",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 366,
			"versionNonce": 2070785647,
			"isDeleted": false,
			"id": "wBFL5keu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 87.2562993231942,
			"y": 88.69160636085618,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.904710614249474,
			"height": 8.933318971989852,
			"seed": 72760,
			"groupIds": [
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "a5234659e85ec41fc3286e272e51f5b8f68eb3dd",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 296,
			"versionNonce": 2120086529,
			"isDeleted": false,
			"id": "jb1eZGnIvDn7VK8f-iWcr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -31.326932763117505,
			"y": 38.606709490007,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 160.01183734374558,
			"height": 63.54674953433048,
			"seed": 1253335794,
			"groupIds": [
				"E5kW_zOq2uuufFA8Q81QQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 251,
			"versionNonce": 363595919,
			"isDeleted": false,
			"id": "Nw6VNOV3B-K0luaskohn2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.692353272373254,
			"y": 106.46240201951068,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 160.0437336159411,
			"height": 19.30915318878402,
			"seed": 1432159150,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 262,
			"versionNonce": 1902234593,
			"isDeleted": false,
			"id": "QzuS2g7w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -17.788960856950432,
			"y": 106.43280166716937,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 137,
			"height": 20,
			"seed": 498403694,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Converting Bases",
			"rawText": "Converting Bases",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Converting Bases"
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 660217519,
			"isDeleted": false,
			"id": "CtYc70tg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23.514198495182974,
			"y": 126.89057645875096,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 147,
			"height": 100,
			"seed": 1934469614,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1. Convert to\n  Decimal\n2. Convert decimal\n   Number (n) to \n   base R",
			"rawText": "1. Convert to\n  Decimal\n2. Convert decimal\n   Number (n) to \n   base R",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1. Convert to\n  Decimal\n2. Convert decimal\n   Number (n) to \n   base R"
		},
		{
			"type": "freedraw",
			"version": 399,
			"versionNonce": 702523329,
			"isDeleted": false,
			"id": "FlMdVFEZjg26skHzfCEwX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -11.13772332400086,
			"y": 222.82600176714203,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 127.89183330155217,
			"height": 31.01302351989537,
			"seed": 535782322,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					8.326672684688674e-17,
					0.29535762189249226
				],
				[
					1.1102230246251565e-16,
					0.5907265109560171
				],
				[
					0,
					0.8860841328485094
				],
				[
					3.3306690738754696e-16,
					1.1814530219120627
				],
				[
					3.3306690738754696e-16,
					1.4768106438045265
				],
				[
					0.29538015623458613,
					2.067537154760572
				],
				[
					0.590737778127079,
					2.3628947766530644
				],
				[
					0.5907377781270782,
					2.9536212876090815
				],
				[
					0.8860954000195629,
					2.953621287609082
				],
				[
					0.8860954000195636,
					3.248978909501574
				],
				[
					0.8860954000195633,
					3.544347798565099
				],
				[
					0.8860954000195638,
					3.8397054204575913
				],
				[
					1.1814530219120558,
					4.135074309521144
				],
				[
					1.181453021912055,
					4.430431931413608
				],
				[
					1.4768106438045394,
					4.430431931413608
				],
				[
					1.4768106438045407,
					4.7257895533061
				],
				[
					1.4768106438045416,
					5.021158442369654
				],
				[
					1.7721908000391273,
					5.021158442369654
				],
				[
					1.7721908000391264,
					5.316516064262146
				],
				[
					2.067548421931619,
					5.316516064262146
				],
				[
					2.0675484219316185,
					5.611884953325671
				],
				[
					2.0675484219316185,
					5.907242575218163
				],
				[
					2.362906043824103,
					5.907242575218163
				],
				[
					2.658263665716596,
					6.202600197110656
				],
				[
					2.9536212876090806,
					6.497969086174181
				],
				[
					3.2490014438436683,
					7.088695597130226
				],
				[
					3.5443590657361597,
					7.3840532190226895
				],
				[
					3.839716687628645,
					7.3840532190226895
				],
				[
					4.135074309521137,
					7.679410840915182
				],
				[
					4.430431931413622,
					7.974779729978735
				],
				[
					5.0211697095407,
					7.974779729978735
				],
				[
					5.0211697095407,
					8.270137351871227
				],
				[
					5.316527331433186,
					8.565506240934752
				],
				[
					5.907242575218163,
					8.860863862827244
				],
				[
					6.202622731452749,
					9.156221484719737
				],
				[
					6.497980353345241,
					9.451590373783262
				],
				[
					6.793337975237726,
					9.451590373783262
				],
				[
					7.088695597130219,
					9.451590373783262
				],
				[
					7.384053219022704,
					9.746947995675754
				],
				[
					7.974790997149782,
					9.746947995675754
				],
				[
					7.974790997149782,
					10.042316884739307
				],
				[
					8.270148619042267,
					10.337674506631771
				],
				[
					8.860863862827244,
					10.337674506631771
				],
				[
					9.451601640954323,
					10.337674506631771
				],
				[
					9.746959262846808,
					10.633032128524263
				],
				[
					10.337674506631785,
					10.633032128524263
				],
				[
					10.928412284758863,
					10.928401017587817
				],
				[
					11.51912752854384,
					10.928401017587817
				],
				[
					11.814485150436326,
					10.928401017587817
				],
				[
					12.405222928563404,
					10.928401017587817
				],
				[
					12.70058055045589,
					11.223758639480309
				],
				[
					12.995938172348382,
					11.223758639480309
				],
				[
					13.291295794240867,
					11.223758639480309
				],
				[
					13.882033572367945,
					11.223758639480309
				],
				[
					14.472748816152922,
					11.223758639480309
				],
				[
					14.768106438045407,
					11.223758639480309
				],
				[
					15.063486594279993,
					11.223758639480309
				],
				[
					15.358844216172486,
					11.223758639480309
				],
				[
					15.65420183806497,
					11.223758639480309
				],
				[
					15.949559459957463,
					11.223758639480309
				],
				[
					16.540297238084534,
					11.223758639480309
				],
				[
					16.835654859977026,
					11.223758639480309
				],
				[
					17.426370103762004,
					11.223758639480309
				],
				[
					18.017107881889075,
					11.223758639480309
				],
				[
					18.312465503781567,
					11.223758639480309
				],
				[
					18.903180747566545,
					11.223758639480309
				],
				[
					19.493918525693616,
					11.223758639480309
				],
				[
					19.7892761475861,
					11.223758639480309
				],
				[
					20.084633769478593,
					11.223758639480309
				],
				[
					20.379991391371085,
					11.223758639480309
				],
				[
					20.675349013263578,
					11.223758639480309
				],
				[
					20.970729169498163,
					11.223758639480309
				],
				[
					21.26608679139064,
					11.223758639480309
				],
				[
					21.561444413283134,
					10.928401017587817
				],
				[
					21.856802035175626,
					10.928401017587817
				],
				[
					22.15215965706812,
					10.928401017587817
				],
				[
					22.447539813302704,
					10.928401017587817
				],
				[
					23.038255057087675,
					10.633032128524263
				],
				[
					23.333612678980167,
					10.633032128524263
				],
				[
					23.924350457107245,
					10.633032128524263
				],
				[
					24.219708078999723,
					10.633032128524263
				],
				[
					24.810423322784708,
					10.633032128524263
				],
				[
					24.810423322784708,
					10.337674506631771
				],
				[
					25.401138566569678,
					10.337674506631771
				],
				[
					25.696518722804264,
					10.042316884739307
				],
				[
					26.28723396658925,
					10.042316884739307
				],
				[
					26.582614122823834,
					10.042316884739307
				],
				[
					26.87794921037422,
					9.746947995675754
				],
				[
					27.173329366608804,
					9.746947995675754
				],
				[
					27.468709522843405,
					9.746947995675754
				],
				[
					27.76404461039379,
					9.746947995675754
				],
				[
					28.059424766628375,
					9.746947995675754
				],
				[
					28.35475985417876,
					9.746947995675754
				],
				[
					28.945520166647945,
					9.451590373783262
				],
				[
					29.24085525419833,
					9.451590373783262
				],
				[
					29.536235410432916,
					9.156221484719737
				],
				[
					29.8315704979833,
					9.156221484719737
				],
				[
					30.126950654217886,
					9.156221484719737
				],
				[
					30.71766589800287,
					9.156221484719737
				],
				[
					31.013046054237456,
					9.156221484719737
				],
				[
					31.30838114178784,
					9.156221484719737
				],
				[
					31.603761298022427,
					8.860863862827244
				],
				[
					31.899141454257027,
					8.860863862827244
				],
				[
					32.489856698042,
					8.860863862827244
				],
				[
					32.78519178559238,
					8.860863862827244
				],
				[
					33.08057194182697,
					8.860863862827244
				],
				[
					33.37595209806157,
					8.860863862827244
				],
				[
					34.26200242939692,
					8.860863862827244
				],
				[
					34.55738258563151,
					8.860863862827244
				],
				[
					34.85276274186611,
					8.860863862827244
				],
				[
					35.14809782941649,
					8.860863862827244
				],
				[
					35.73881307320146,
					8.860863862827244
				],
				[
					36.03419322943605,
					8.860863862827244
				],
				[
					36.32957338567065,
					8.860863862827244
				],
				[
					36.62490847322103,
					8.860863862827244
				],
				[
					36.92028862945562,
					8.860863862827244
				],
				[
					37.215623717006004,
					8.860863862827244
				],
				[
					37.51100387324059,
					8.860863862827244
				],
				[
					37.80638402947519,
					8.860863862827244
				],
				[
					38.101719117025574,
					8.860863862827244
				],
				[
					38.692434360810545,
					8.860863862827244
				],
				[
					39.28319467327973,
					8.860863862827244
				],
				[
					39.578529760830115,
					8.860863862827244
				],
				[
					40.169245004615085,
					8.860863862827244
				],
				[
					40.76000531708427,
					8.860863862827244
				],
				[
					41.35072056086924,
					8.860863862827244
				],
				[
					41.646055648419626,
					8.860863862827244
				],
				[
					41.94143580465421,
					8.860863862827244
				],
				[
					42.23681596088881,
					8.860863862827244
				],
				[
					42.23681596088881,
					9.156221484719737
				],
				[
					42.5321510484392,
					9.156221484719737
				],
				[
					42.5321510484392,
					9.451590373783262
				],
				[
					42.82753120467378,
					9.451590373783262
				],
				[
					43.12286629222417,
					9.451590373783262
				],
				[
					43.12286629222417,
					9.746947995675754
				],
				[
					43.41824644845875,
					10.042316884739307
				],
				[
					43.71362660469335,
					10.042316884739307
				],
				[
					43.71362660469335,
					10.337674506631771
				],
				[
					44.00896169224374,
					10.633032128524263
				],
				[
					44.30434184847832,
					10.928401017587817
				],
				[
					44.59967693602871,
					11.223758639480309
				],
				[
					44.89505709226329,
					11.519127528543834
				],
				[
					45.190437248497894,
					11.519127528543834
				],
				[
					45.190437248497894,
					11.814485150436326
				],
				[
					45.48577233604828,
					12.109842772328818
				],
				[
					45.781152492282864,
					12.405211661392343
				],
				[
					46.07648757983325,
					12.700569283284835
				],
				[
					46.371867736067834,
					12.995938172348389
				],
				[
					46.667247892302434,
					12.995938172348389
				],
				[
					46.667247892302434,
					13.291295794240853
				],
				[
					46.667247892302434,
					13.586653416133345
				],
				[
					46.96258297985282,
					13.882022305196898
				],
				[
					47.257963136087405,
					14.17737992708939
				],
				[
					47.257963136087405,
					14.472748816152915
				],
				[
					47.257963136087405,
					14.768106438045407
				],
				[
					47.55329822363779,
					15.0634640599379
				],
				[
					47.848678379872375,
					15.358832949001425
				],
				[
					48.144058536106975,
					15.654190570893917
				],
				[
					48.144058536106975,
					15.94955945995747
				],
				[
					48.144058536106975,
					16.244917081849934
				],
				[
					48.43939362365736,
					16.540274703742426
				],
				[
					48.43939362365736,
					16.83564359280598
				],
				[
					48.734773779891945,
					17.131001214698472
				],
				[
					48.734773779891945,
					17.426370103761997
				],
				[
					48.734773779891945,
					17.72172772565449
				],
				[
					48.734773779891945,
					18.01708534754698
				],
				[
					48.734773779891945,
					18.312454236610506
				],
				[
					49.03010886744233,
					18.312454236610506
				],
				[
					49.03010886744233,
					18.607811858503
				],
				[
					49.325489023676916,
					18.90318074756655
				],
				[
					49.325489023676916,
					19.198538369459015
				],
				[
					49.620869179911516,
					19.78926488041506
				],
				[
					49.620869179911516,
					20.379991391371078
				],
				[
					49.620869179911516,
					20.970706635156063
				],
				[
					49.9162042674619,
					20.970706635156063
				],
				[
					49.9162042674619,
					21.56143314611208
				],
				[
					49.9162042674619,
					21.856802035175633
				],
				[
					50.211584423696486,
					22.152159657068097
				],
				[
					50.211584423696486,
					22.44751727896059
				],
				[
					50.211584423696486,
					23.038243789916635
				],
				[
					50.211584423696486,
					23.3336014118091
				],
				[
					50.211584423696486,
					23.628981568043713
				],
				[
					50.211584423696486,
					23.924339189936177
				],
				[
					50.50691951124687,
					24.21969681182867
				],
				[
					50.50691951124687,
					24.810412055613654
				],
				[
					50.802299667481456,
					25.40114983374073
				],
				[
					50.802299667481456,
					25.696507455633224
				],
				[
					50.802299667481456,
					26.28722269941818
				],
				[
					50.802299667481456,
					26.582602855652794
				],
				[
					50.802299667481456,
					26.87796047754526
				],
				[
					51.09767982371606,
					27.17331809943775
				],
				[
					51.09767982371606,
					27.468675721330243
				],
				[
					51.09767982371606,
					27.764033343222735
				],
				[
					51.09767982371606,
					28.05941349945732
				],
				[
					51.09767982371606,
					28.354771121349813
				],
				[
					51.39301491126644,
					28.354771121349813
				],
				[
					51.39301491126644,
					28.650128743242306
				],
				[
					51.39301491126644,
					28.945486365134798
				],
				[
					51.39301491126644,
					28.650128743242306
				],
				[
					51.39301491126644,
					28.354771121349813
				],
				[
					51.68839506750103,
					28.05941349945732
				],
				[
					51.68839506750103,
					27.764033343222735
				],
				[
					51.68839506750103,
					27.17331809943775
				],
				[
					51.98373015505141,
					26.87796047754526
				],
				[
					51.98373015505141,
					26.582602855652794
				],
				[
					52.279110311286,
					26.582602855652794
				],
				[
					52.279110311286,
					26.28722269941818
				],
				[
					52.279110311286,
					25.991865077525716
				],
				[
					52.279110311286,
					25.696507455633224
				],
				[
					52.5744904675206,
					25.696507455633224
				],
				[
					52.86982555507098,
					25.10579221184824
				],
				[
					52.86982555507098,
					24.810412055613654
				],
				[
					53.16520571130557,
					24.810412055613654
				],
				[
					53.16520571130557,
					24.21969681182867
				],
				[
					53.46054079885595,
					23.924339189936177
				],
				[
					53.46054079885595,
					23.628981568043713
				],
				[
					53.75592095509054,
					23.628981568043713
				],
				[
					53.75592095509054,
					23.3336014118091
				],
				[
					53.75592095509054,
					23.038243789916635
				],
				[
					54.05130111132514,
					22.742886168024143
				],
				[
					54.34663619887552,
					22.44751727896059
				],
				[
					54.64201635511011,
					22.152159657068097
				],
				[
					54.93735144266049,
					21.856802035175633
				],
				[
					55.23273159889508,
					21.56143314611208
				],
				[
					55.23273159889508,
					21.266075524219588
				],
				[
					55.52811175512968,
					21.266075524219588
				],
				[
					55.82344684268006,
					20.970706635156063
				],
				[
					55.82344684268006,
					20.67534901326357
				],
				[
					56.11882699891465,
					20.67534901326357
				],
				[
					56.11882699891465,
					20.379991391371078
				],
				[
					56.11882699891465,
					20.084622502307553
				],
				[
					56.41416208646503,
					20.084622502307553
				],
				[
					56.70954224269962,
					20.084622502307553
				],
				[
					56.70954224269962,
					19.78926488041506
				],
				[
					57.00492239893422,
					19.493895991351508
				],
				[
					57.300257486484604,
					19.198538369459015
				],
				[
					57.59563764271919,
					19.198538369459015
				],
				[
					57.59563764271919,
					18.90318074756655
				],
				[
					57.890972730269574,
					18.607811858503
				],
				[
					58.18635288650416,
					18.607811858503
				],
				[
					58.18635288650416,
					18.312454236610506
				],
				[
					58.48173304273876,
					18.312454236610506
				],
				[
					58.48173304273876,
					18.01708534754698
				],
				[
					58.777068130289145,
					18.01708534754698
				],
				[
					59.07244828652373,
					17.72172772565449
				],
				[
					59.367783374074115,
					17.72172772565449
				],
				[
					59.6631635303087,
					17.72172772565449
				],
				[
					59.6631635303087,
					17.426370103761997
				],
				[
					59.9585436865433,
					17.426370103761997
				],
				[
					60.253878774093685,
					17.131001214698472
				],
				[
					61.43535433034784,
					17.131001214698472
				],
				[
					62.3214046616832,
					17.131001214698472
				],
				[
					62.61678481791778,
					17.131001214698472
				],
				[
					63.20750006170277,
					17.131001214698472
				],
				[
					64.09359546172232,
					16.83564359280598
				],
				[
					64.97969086174189,
					16.83564359280598
				],
				[
					66.75183659309681,
					16.540274703742426
				],
				[
					67.0472167493314,
					16.540274703742426
				],
				[
					67.63793199311638,
					16.244917081849934
				],
				[
					68.52402739313595,
					16.244917081849934
				],
				[
					69.11474263692094,
					16.244917081849934
				],
				[
					69.41012279315552,
					16.244917081849934
				],
				[
					69.7054578807059,
					16.244917081849934
				],
				[
					70.2962181931751,
					16.244917081849934
				],
				[
					70.59155328072546,
					16.244917081849934
				],
				[
					70.88693343696005,
					16.244917081849934
				],
				[
					71.18226852451045,
					16.244917081849934
				],
				[
					71.77302883697962,
					16.244917081849934
				],
				[
					72.3637440807646,
					16.244917081849934
				],
				[
					72.65907916831497,
					16.244917081849934
				],
				[
					73.54517456833455,
					16.244917081849934
				],
				[
					74.13588981211953,
					16.244917081849934
				],
				[
					74.7266501245887,
					16.244917081849934
				],
				[
					75.61270045592406,
					16.540274703742426
				],
				[
					76.20346076839326,
					16.540274703742426
				],
				[
					76.79417601217821,
					16.83564359280598
				],
				[
					77.3848912559632,
					16.83564359280598
				],
				[
					77.97560649974818,
					16.83564359280598
				],
				[
					78.86170189976772,
					16.83564359280598
				],
				[
					79.7477972997873,
					17.131001214698472
				],
				[
					80.63389269980686,
					17.131001214698472
				],
				[
					81.51994303114222,
					17.131001214698472
				],
				[
					82.40603843116179,
					17.131001214698472
				],
				[
					83.29213383118136,
					17.131001214698472
				],
				[
					84.47356431875133,
					17.131001214698472
				],
				[
					85.0643246312205,
					17.131001214698472
				],
				[
					85.95037496255586,
					17.131001214698472
				],
				[
					86.83647036257543,
					17.131001214698472
				],
				[
					88.01794591882958,
					17.131001214698472
				],
				[
					89.19937640639952,
					17.131001214698472
				],
				[
					89.49475656263411,
					17.131001214698472
				],
				[
					90.0854718064191,
					17.131001214698472
				],
				[
					90.38080689396949,
					17.131001214698472
				],
				[
					91.26690229398903,
					16.83564359280598
				],
				[
					91.56228245022362,
					16.83564359280598
				],
				[
					93.33442818157857,
					16.83564359280598
				],
				[
					93.62980833781316,
					16.83564359280598
				],
				[
					94.5159037378327,
					16.83564359280598
				],
				[
					95.40199913785227,
					16.83564359280598
				],
				[
					95.99271438163726,
					16.83564359280598
				],
				[
					96.87880978165683,
					16.540274703742426
				],
				[
					97.76486011299218,
					16.540274703742426
				],
				[
					98.35562042546135,
					16.540274703742426
				],
				[
					99.24167075679674,
					16.244917081849934
				],
				[
					99.83243106926591,
					16.244917081849934
				],
				[
					100.71848140060126,
					16.244917081849934
				],
				[
					101.01386155683585,
					15.94955945995747
				],
				[
					101.89995695685542,
					15.654190570893917
				],
				[
					102.4906722006404,
					15.654190570893917
				],
				[
					103.37676760065995,
					15.358832949001425
				],
				[
					103.96748284444493,
					15.0634640599379
				],
				[
					104.8535782444645,
					14.768106438045407
				],
				[
					105.44429348824949,
					14.472748816152915
				],
				[
					106.33038888826903,
					14.17737992708939
				],
				[
					106.92110413205401,
					14.17737992708939
				],
				[
					107.80719953207358,
					13.586653416133345
				],
				[
					108.69329493209315,
					13.291295794240853
				],
				[
					109.28401017587811,
					13.291295794240853
				],
				[
					109.8747254196631,
					12.995938172348389
				],
				[
					110.76082081968266,
					12.700569283284835
				],
				[
					111.9422513072526,
					12.109842772328818
				],
				[
					112.82834670727217,
					11.814485150436326
				],
				[
					113.41906195105716,
					11.223758639480309
				],
				[
					113.71444210729175,
					11.223758639480309
				],
				[
					114.30515735107673,
					10.928401017587817
				],
				[
					114.89587259486169,
					10.633032128524263
				],
				[
					115.48658783864667,
					10.337674506631771
				],
				[
					116.37268323866624,
					9.746947995675754
				],
				[
					117.25877863868581,
					9.156221484719737
				],
				[
					117.84949388247077,
					8.860863862827244
				],
				[
					118.14487403870535,
					8.270137351871227
				],
				[
					118.44020912625575,
					8.270137351871227
				],
				[
					119.32630452627532,
					7.679410840915182
				],
				[
					119.9170197700603,
					7.088695597130226
				],
				[
					120.50778008252948,
					6.793326708066672
				],
				[
					120.80311517007985,
					6.49796908617418
				],
				[
					121.39383041386483,
					6.202600197110655
				],
				[
					121.39383041386483,
					5.907242575218163
				],
				[
					121.984590726334,
					5.316516064262146
				],
				[
					122.2799258138844,
					5.316516064262146
				],
				[
					122.57530597011899,
					4.7257895533061
				],
				[
					122.87064105766939,
					4.430431931413608
				],
				[
					123.16602121390397,
					3.839705420457591
				],
				[
					123.75673645768893,
					3.5443477985650986
				],
				[
					123.75673645768893,
					3.2489789095015738
				],
				[
					124.34745170147391,
					2.6582636657165892
				],
				[
					124.93821201394309,
					2.067537154760572
				],
				[
					125.23354710149349,
					1.7721682656970188
				],
				[
					125.52892725772807,
					1.4768106438045265
				],
				[
					125.82426234527847,
					1.1814530219120627
				],
				[
					126.11964250151306,
					0.5907265109560171
				],
				[
					126.41502265774764,
					0.29535762189249226
				],
				[
					126.41502265774764,
					0
				],
				[
					126.71035774529801,
					-0.29535762189249226
				],
				[
					127.301072989083,
					-0.8860841328485094
				],
				[
					127.301072989083,
					-1.1814530219120627
				],
				[
					127.301072989083,
					-1.476810643804555
				],
				[
					127.59645314531758,
					-1.7721682656970188
				],
				[
					127.89183330155217,
					-1.7721682656970188
				],
				[
					127.89183330155217,
					-2.067537154760572
				],
				[
					127.89183330155217,
					-2.067537154760572
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 136,
			"versionNonce": 589328591,
			"isDeleted": false,
			"id": "VHM11Bj2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -19.66010797993551,
			"y": 256.67673441589193,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 149,
			"height": 120,
			"seed": 65098738,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "divide n by r.\nremainder = x0\ndivide result by r\nremainder = x1\nrepeat until result\n= 0",
			"rawText": "divide n by r.\nremainder = x0\ndivide result by r\nremainder = x1\nrepeat until result\n= 0",
			"baseline": 115,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "divide n by r.\nremainder = x0\ndivide result by r\nremainder = x1\nrepeat until result\n= 0"
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 1912014753,
			"isDeleted": false,
			"id": "RmTIvXhl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140.90074230211303,
			"y": 141.24179075172555,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 130,
			"height": 20,
			"seed": 1762586350,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "BcKVGZXlKQoZFWIkP5V4i",
					"type": "arrow"
				}
			],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Fractional Part:",
			"rawText": "Fractional Part:",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Fractional Part:"
		},
		{
			"type": "freedraw",
			"version": 181,
			"versionNonce": 311918319,
			"isDeleted": false,
			"id": "0oXsoGDzd6yhyUjaYKuij",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 120.60811303771186,
			"y": 163.76144947173606,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 10.599914117318178,
			"height": 45.42815384717662,
			"seed": 357518578,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3785910546803706,
					0
				],
				[
					0.3785910546803706,
					0.37857661345918814
				],
				[
					0.7571243444759972,
					0.7571387856971796
				],
				[
					1.1357153991563675,
					0.7571387856971796
				],
				[
					1.892839743632365,
					1.1357009579351711
				],
				[
					1.8928397436323647,
					1.514277571394359
				],
				[
					2.649964088108348,
					1.5142775713943593
				],
				[
					2.6499640881083484,
					1.89283974363235
				],
				[
					3.0285551427887185,
					2.271416357091539
				],
				[
					3.407088432584345,
					2.6499785293295304
				],
				[
					3.7856794872647166,
					2.6499785293295304
				],
				[
					3.7856794872647153,
					3.0285407015675214
				],
				[
					4.164270541945087,
					3.4071173150267113
				],
				[
					4.164270541945086,
					3.78567948726473
				],
				[
					4.542803831740713,
					3.7856794872647295
				],
				[
					4.542803831740713,
					4.16425610072389
				],
				[
					4.542803831740712,
					4.5428182729619095
				],
				[
					4.542803831740714,
					4.921380445199901
				],
				[
					4.542803831740713,
					5.299957058659089
				],
				[
					4.921394886421083,
					5.299957058659091
				],
				[
					4.921394886421082,
					5.678519230897081
				],
				[
					4.921394886421084,
					6.057095844356269
				],
				[
					5.299928176216696,
					6.057095844356269
				],
				[
					5.299928176216696,
					6.43565801659426
				],
				[
					5.678519230897081,
					7.19279680229144
				],
				[
					5.678519230897081,
					7.571358974529431
				],
				[
					5.678519230897081,
					7.9499355879886195
				],
				[
					6.057110285577451,
					8.328497760226611
				],
				[
					6.057110285577451,
					8.707059932464603
				],
				[
					6.057110285577451,
					9.08563654592379
				],
				[
					6.435643575373064,
					9.464198718161782
				],
				[
					6.435643575373064,
					9.84277533162097
				],
				[
					6.435643575373064,
					10.221337503858962
				],
				[
					6.435643575373064,
					10.599899676096982
				],
				[
					6.435643575373064,
					10.978476289556141
				],
				[
					6.435643575373064,
					11.357038461794161
				],
				[
					6.435643575373064,
					11.73561507525335
				],
				[
					6.814234630053448,
					11.73561507525335
				],
				[
					6.814234630053448,
					12.114177247491341
				],
				[
					6.814234630053448,
					12.492739419729332
				],
				[
					6.814234630053448,
					12.87131603318852
				],
				[
					6.814234630053448,
					13.249878205426512
				],
				[
					6.814234630053448,
					13.6284548188857
				],
				[
					6.814234630053448,
					14.007016991123692
				],
				[
					6.814234630053448,
					14.385579163361683
				],
				[
					6.814234630053448,
					14.764155776820871
				],
				[
					6.814234630053448,
					15.142717949058863
				],
				[
					6.814234630053448,
					15.521294562518051
				],
				[
					6.814234630053448,
					15.899856734756042
				],
				[
					6.814234630053448,
					16.278418906994034
				],
				[
					6.814234630053448,
					16.656995520453222
				],
				[
					6.435643575373064,
					16.656995520453222
				],
				[
					6.435643575373064,
					17.035557692691214
				],
				[
					6.435643575373064,
					17.4141343061504
				],
				[
					6.057110285577451,
					17.4141343061504
				],
				[
					6.057110285577451,
					17.79269647838842
				],
				[
					6.057110285577451,
					18.171258650626413
				],
				[
					6.057110285577451,
					18.5498352640856
				],
				[
					6.057110285577451,
					18.928397436323593
				],
				[
					5.678519230897081,
					19.30697404978278
				],
				[
					5.678519230897081,
					19.685536222020772
				],
				[
					5.299928176216696,
					19.685536222020772
				],
				[
					5.299928176216696,
					20.064098394258764
				],
				[
					5.299928176216696,
					20.442675007717952
				],
				[
					4.9213948864210835,
					20.442675007717952
				],
				[
					4.9213948864210835,
					20.821237179955943
				],
				[
					4.9213948864210835,
					21.19981379341513
				],
				[
					5.299928176216696,
					21.19981379341513
				],
				[
					5.299928176216696,
					21.578375965653123
				],
				[
					5.678519230897081,
					21.578375965653123
				],
				[
					6.057110285577451,
					21.578375965653123
				],
				[
					6.435643575373064,
					21.956938137891115
				],
				[
					6.814234630053448,
					21.956938137891115
				],
				[
					7.192767919849061,
					21.956938137891115
				],
				[
					7.571358974529431,
					21.956938137891115
				],
				[
					7.949950029209788,
					21.956938137891115
				],
				[
					8.328483319005443,
					22.335514751350303
				],
				[
					8.7070743736858,
					22.335514751350303
				],
				[
					8.7070743736858,
					22.714076923588294
				],
				[
					9.085607663481426,
					22.714076923588294
				],
				[
					9.46419871816181,
					22.714076923588294
				],
				[
					9.46419871816181,
					23.092653537047482
				],
				[
					9.842789772842167,
					23.092653537047482
				],
				[
					10.221323062637794,
					23.092653537047482
				],
				[
					10.221323062637794,
					23.471215709285474
				],
				[
					10.599914117318178,
					23.471215709285474
				],
				[
					10.599914117318178,
					23.849777881523494
				],
				[
					10.599914117318178,
					24.228354494982653
				],
				[
					10.221323062637794,
					24.606916667220673
				],
				[
					9.842789772842167,
					24.98549328067986
				],
				[
					9.46419871816181,
					24.98549328067986
				],
				[
					9.085607663481426,
					24.98549328067986
				],
				[
					8.7070743736858,
					24.98549328067986
				],
				[
					8.7070743736858,
					25.364055452917853
				],
				[
					8.328483319005443,
					25.364055452917853
				],
				[
					7.949950029209788,
					25.364055452917853
				],
				[
					7.571358974529431,
					25.364055452917853
				],
				[
					7.192767919849061,
					25.364055452917853
				],
				[
					6.814234630053448,
					25.364055452917853
				],
				[
					6.435643575373064,
					25.742617625155845
				],
				[
					6.057110285577451,
					25.742617625155845
				],
				[
					5.678519230897081,
					25.742617625155845
				],
				[
					5.299928176216696,
					25.742617625155845
				],
				[
					5.299928176216696,
					26.121194238615033
				],
				[
					5.299928176216696,
					26.499756410853024
				],
				[
					5.299928176216696,
					26.878333024312212
				],
				[
					5.678519230897081,
					26.878333024312212
				],
				[
					5.678519230897081,
					27.256895196550204
				],
				[
					5.678519230897081,
					27.635457368788195
				],
				[
					6.057110285577451,
					28.014033982247383
				],
				[
					6.057110285577451,
					28.392596154485375
				],
				[
					6.435643575373064,
					28.771172767944563
				],
				[
					6.435643575373064,
					29.149734940182555
				],
				[
					6.435643575373064,
					29.528297112420546
				],
				[
					6.435643575373064,
					29.906873725879734
				],
				[
					6.435643575373064,
					30.285435898117726
				],
				[
					6.435643575373064,
					31.042574683814934
				],
				[
					6.435643575373064,
					31.421136856052925
				],
				[
					6.814234630053448,
					31.799713469512113
				],
				[
					6.814234630053448,
					32.178275641750105
				],
				[
					6.814234630053448,
					32.55685225520929
				],
				[
					6.814234630053448,
					32.935414427447284
				],
				[
					6.814234630053448,
					33.313976599685276
				],
				[
					6.814234630053448,
					33.692553213144464
				],
				[
					6.814234630053448,
					34.071115385382456
				],
				[
					6.814234630053448,
					34.828254171079635
				],
				[
					6.814234630053448,
					35.20681634331763
				],
				[
					6.814234630053448,
					35.585392956776815
				],
				[
					6.814234630053448,
					35.963955129014806
				],
				[
					6.814234630053448,
					36.342531742473994
				],
				[
					6.814234630053448,
					36.721093914711986
				],
				[
					6.814234630053448,
					37.099656086950006
				],
				[
					6.814234630053448,
					37.478232700409166
				],
				[
					6.814234630053448,
					37.856794872647185
				],
				[
					6.814234630053448,
					38.235371486106345
				],
				[
					6.814234630053448,
					38.613933658344365
				],
				[
					6.814234630053448,
					38.99249583058236
				],
				[
					6.814234630053448,
					39.371072444041545
				],
				[
					6.814234630053448,
					39.749634616279536
				],
				[
					6.814234630053448,
					40.128211229738724
				],
				[
					6.435643575373064,
					40.506773401976716
				],
				[
					6.057110285577451,
					40.506773401976716
				],
				[
					6.057110285577451,
					40.88533557421471
				],
				[
					6.057110285577451,
					41.263912187673895
				],
				[
					5.678519230897081,
					41.64247435991189
				],
				[
					5.299928176216696,
					41.64247435991189
				],
				[
					5.299928176216696,
					42.021050973371075
				],
				[
					4.9213948864210835,
					42.021050973371075
				],
				[
					4.9213948864210835,
					42.39961314560907
				],
				[
					4.542803831740713,
					42.39961314560907
				],
				[
					4.164270541945086,
					43.156751931306246
				],
				[
					3.7856794872647157,
					43.53531410354424
				],
				[
					3.407088432584345,
					43.53531410354424
				],
				[
					3.0285551427887185,
					43.913890717003426
				],
				[
					3.0285551427887185,
					44.29245288924142
				],
				[
					2.649964088108348,
					44.29245288924142
				],
				[
					2.649964088108348,
					44.67101506147944
				],
				[
					2.2714307983127355,
					44.67101506147944
				],
				[
					2.2714307983127355,
					45.049591674938625
				],
				[
					2.2714307983127355,
					45.42815384717662
				],
				[
					1.892839743632365,
					45.42815384717662
				],
				[
					1.5142486889519802,
					45.42815384717662
				],
				[
					1.5142486889519802,
					45.42815384717662
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "arrow",
			"version": 106,
			"versionNonce": 601320321,
			"isDeleted": false,
			"id": "BcKVGZXlKQoZFWIkP5V4i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 89.57087589151746,
			"y": 147.27755627328273,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 50.96640026190494,
			"height": 18.34789631743027,
			"seed": 1777843890,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "RmTIvXhl",
				"focus": 1.3725443787100493,
				"gap": 12.312130795873088
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					50.96640026190494,
					-18.34789631743027
				]
			]
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 944228623,
			"isDeleted": false,
			"id": "ba6NhXMl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 145.6852800643321,
			"y": 159.46939884073805,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 126,
			"height": 140,
			"seed": 567462958,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "decimal * r\nwhole # = x(-1)\nresult -   * r\nwhole # = x(-2)\nrepeat until 0\nor sufficient\naccuracy",
			"rawText": "decimal * r\nwhole # = x(-1)\nresult -   * r\nwhole # = x(-2)\nrepeat until 0\nor sufficient\naccuracy",
			"baseline": 135,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "decimal * r\nwhole # = x(-1)\nresult -   * r\nwhole # = x(-2)\nrepeat until 0\nor sufficient\naccuracy"
		},
		{
			"type": "arrow",
			"version": 133,
			"versionNonce": 666915681,
			"isDeleted": false,
			"id": "OGi-3BOvY4v-KZIf4twE8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 217.1318284077604,
			"y": 208.4586585470438,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 13.287789169700716,
			"height": 12.051711920577702,
			"seed": 52978802,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-13.287789169700716,
					-12.051711920577702
				]
			]
		},
		{
			"type": "line",
			"version": 135,
			"versionNonce": 1906954031,
			"isDeleted": false,
			"id": "tW1Ldgqen-9XEnXrGRyJb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -31.178798247939895,
			"y": 126.1401193887266,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 1.4049454764951577,
			"height": 250.08412687540323,
			"seed": 1120672110,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.4049454764951577,
					250.08412687540323
				]
			]
		},
		{
			"type": "line",
			"version": 81,
			"versionNonce": 838942529,
			"isDeleted": false,
			"id": "bdnGMg8Y7_iG9L0zGvRv2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -33.28621646268266,
			"y": 376.92671900237735,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 169.29850248892143,
			"height": 2.1074182147427223,
			"seed": 1361230766,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					169.29850248892143,
					-2.1074182147427223
				]
			]
		},
		{
			"type": "line",
			"version": 87,
			"versionNonce": 1495667023,
			"isDeleted": false,
			"id": "nbVRlhRLlrlhuxLGDwrFB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.71481235972084,
			"y": 375.5217735258822,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 1.404945476495186,
			"height": 73.05829027767226,
			"seed": 1910627822,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.404945476495186,
					-73.05829027767226
				]
			]
		},
		{
			"type": "line",
			"version": 131,
			"versionNonce": 1090105121,
			"isDeleted": false,
			"id": "J2jLlryBx0m0rH8IhzgOq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 135.30986688322565,
			"y": 301.76101050996243,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 141.199110601908,
			"height": 1.4049454764951292,
			"seed": 1540833006,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					141.199110601908,
					1.4049454764951292
				]
			]
		},
		{
			"type": "line",
			"version": 155,
			"versionNonce": 672468847,
			"isDeleted": false,
			"id": "n3s_Ehykk59XFuBZGCQEq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 278.45630401185105,
			"y": 303.9409818272144,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 0.15627834227387893,
			"height": 165.51026415595547,
			"seed": 1311717742,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.15627834227387893,
					-165.51026415595547
				]
			]
		},
		{
			"type": "line",
			"version": 158,
			"versionNonce": 1528374017,
			"isDeleted": false,
			"id": "fdw16pPLRJO7_EcMcbyb8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 278.9328246411777,
			"y": 139.06351664285947,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 153.14141512828917,
			"height": 0.7024995358648312,
			"seed": 620576942,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-153.14141512828917,
					0.7024995358648312
				]
			]
		},
		{
			"type": "line",
			"version": 82,
			"versionNonce": 1488931215,
			"isDeleted": false,
			"id": "nqvGA9gDlKOM5ncbfAFnH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 128.53172857393315,
			"y": 141.2406622194837,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 0.45572287936084876,
			"height": 12.993071020779922,
			"seed": 1671636846,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.45572287936084876,
					-12.993071020779922
				]
			]
		},
		{
			"type": "rectangle",
			"version": 289,
			"versionNonce": 215948001,
			"isDeleted": false,
			"id": "4F4AqQvmAwn6Bd8jnAPta",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 516.6870436374898,
			"y": -21.946689545435106,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 136.43752522902457,
			"height": 25.119259419310993,
			"seed": 1450339438,
			"groupIds": [
				"ABmhG6229u25SkSSml_ae"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 194,
			"versionNonce": 140328879,
			"isDeleted": false,
			"id": "A45Nq2Ea",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 526.5731573155699,
			"y": -19.024313216377863,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 119,
			"height": 20,
			"seed": 1891713010,
			"groupIds": [
				"ABmhG6229u25SkSSml_ae"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Binary Addition",
			"rawText": "Binary Addition",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Binary Addition"
		},
		{
			"type": "text",
			"version": 183,
			"versionNonce": 651892417,
			"isDeleted": false,
			"id": "Liq65LGw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 518.533757116031,
			"y": 7.4426561959845685,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 129,
			"height": 40,
			"seed": 1733446514,
			"groupIds": [
				"ABmhG6229u25SkSSml_ae"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "same as decimal\naddition",
			"rawText": "same as decimal\naddition",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "same as decimal\naddition"
		},
		{
			"type": "rectangle",
			"version": 294,
			"versionNonce": 420966863,
			"isDeleted": false,
			"id": "GPi0cAqVXA5BISCWKumRe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 515.3346608705408,
			"y": 4.812150853002549,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 137.5614639858038,
			"height": 43.18792135026473,
			"seed": 1569729266,
			"groupIds": [
				"ABmhG6229u25SkSSml_ae"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 320,
			"versionNonce": 1001166497,
			"isDeleted": false,
			"id": "Qb_WcTltknAmLx1zeJuYF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 340.8396084580393,
			"y": -22.026683540395254,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 165.51466031875935,
			"height": 24.82719679285617,
			"seed": 918683502,
			"groupIds": [
				"S9NlHyhn7omXepfd_qFiN",
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 207,
			"versionNonce": 335962095,
			"isDeleted": false,
			"id": "NHOPfgPn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 345.5685253056683,
			"y": -19.47757739214677,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 159,
			"height": 20,
			"seed": 386858994,
			"groupIds": [
				"S9NlHyhn7omXepfd_qFiN",
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347335,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Binary Multiplication",
			"rawText": "Binary Multiplication",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Binary Multiplication"
		},
		{
			"type": "text",
			"version": 73,
			"versionNonce": 1577261697,
			"isDeleted": false,
			"id": "QVvKMRtI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 348.39818957215977,
			"y": 9.76785269273853,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 156,
			"height": 40,
			"seed": 296677682,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "110 * 10 : 110*0 = 0\n110 * 1 = 110",
			"rawText": "110 * 10 : 110*0 = 0\n110 * 1 = 110",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "110 * 10 : 110*0 = 0\n110 * 1 = 110"
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 1261603343,
			"isDeleted": false,
			"id": "ArWxLrz9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 465.57626655748277,
			"y": 32.18926696041072,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 35,
			"height": 20,
			"seed": 1900544942,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "000",
			"rawText": "000",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "000"
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 513679969,
			"isDeleted": false,
			"id": "rXZJzQth",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 463.68145343642556,
			"y": 49.7165232482744,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 22,
			"height": 20,
			"seed": 1872706158,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "110",
			"rawText": "110",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "110"
		},
		{
			"type": "line",
			"version": 90,
			"versionNonce": 999583791,
			"isDeleted": false,
			"id": "zctdiSFTLgue76TbEKqFi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 452.3625958792601,
			"y": 68.05942554616556,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 44.645849520178274,
			"height": 0.8811548139897525,
			"seed": 1517241906,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					44.645849520178274,
					0.8811548139897525
				]
			]
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 1246572097,
			"isDeleted": false,
			"id": "j9p3PGxq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 449.7190866187555,
			"y": 49.10423369015723,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 12,
			"height": 20,
			"seed": 1951809838,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "+",
			"rawText": "+",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+"
		},
		{
			"type": "rectangle",
			"version": 197,
			"versionNonce": 789877327,
			"isDeleted": false,
			"id": "LVHR6eTjoHQZcUn1x6vaK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 341.3699934539938,
			"y": 4.234495552505564,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 166.18505692030982,
			"height": 77.85655396600066,
			"seed": 456227630,
			"groupIds": [
				"EB1ruBO4oHn0XDepMMTDm"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 337,
			"versionNonce": 1743765025,
			"isDeleted": false,
			"id": "DKEBrKL4woAJklmX3gygA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 341.8314487434705,
			"y": 91.18556162968665,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 157.24745031348175,
			"height": 23.995554000487942,
			"seed": 647999342,
			"groupIds": [
				"dU4qiz9IlN2oXMUXxRDUP",
				"zgtYrvUlSocJxCqwcWLp5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 282,
			"versionNonce": 512454767,
			"isDeleted": false,
			"id": "ELBDs75S",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 346.9460357501828,
			"y": 92.07793211485034,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 148,
			"height": 20,
			"seed": 1202953198,
			"groupIds": [
				"dU4qiz9IlN2oXMUXxRDUP",
				"zgtYrvUlSocJxCqwcWLp5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Binary Subtraction",
			"rawText": "Binary Subtraction",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Binary Subtraction"
		},
		{
			"type": "text",
			"version": 262,
			"versionNonce": 1987400193,
			"isDeleted": false,
			"id": "m7U2NwBH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 345.4052774491418,
			"y": 114.82871461443705,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 135,
			"height": 100,
			"seed": 1208683630,
			"groupIds": [
				"zgtYrvUlSocJxCqwcWLp5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "same as normal\nsubtraction. Or\ntake complement\nof subtracting #\nand add them",
			"rawText": "same as normal\nsubtraction. Or\ntake complement\nof subtracting #\nand add them",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "same as normal\nsubtraction. Or\ntake complement\nof subtracting #\nand add them"
		},
		{
			"type": "rectangle",
			"version": 427,
			"versionNonce": 1405192847,
			"isDeleted": false,
			"id": "3GoMTdTH5erC6JtyJbFPq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 340.8103381341128,
			"y": 113.64946919183154,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 158.2685609228394,
			"height": 104.92111036284886,
			"seed": 1751681458,
			"groupIds": [
				"zgtYrvUlSocJxCqwcWLp5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 138,
			"versionNonce": 1792895457,
			"isDeleted": false,
			"id": "PzX01xo9P-5Ze0SooO2Kj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 516.0234393808379,
			"y": 53.62161861337668,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 135.10695762394573,
			"height": 38.740344153350975,
			"seed": 360613810,
			"groupIds": [
				"NPT7symF9nhR2dv4AEDO0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "",
			"locked": false
		},
		{
			"type": "text",
			"version": 112,
			"versionNonce": 1265590447,
			"isDeleted": false,
			"id": "NtRDACja",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 532.0267381083049,
			"y": 51.313002557133444,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 111,
			"height": 40,
			"seed": 87662,
			"groupIds": [
				"NPT7symF9nhR2dv4AEDO0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "[[Signed Binary Numbers]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Signed Binary \n  Numbers",
			"rawText": "Signed Binary \n  Numbers",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Signed Binary \n  Numbers"
		},
		{
			"type": "text",
			"version": 55,
			"versionNonce": 1849132481,
			"isDeleted": false,
			"id": "xynq8Obp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 523.6475061375999,
			"y": 95.08750163886444,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 108,
			"height": 40,
			"seed": 314402542,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0 in MSB = +\n1 in MSB = -",
			"rawText": "0 in MSB = +\n1 in MSB = -",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0 in MSB = +\n1 in MSB = -"
		},
		{
			"type": "rectangle",
			"version": 172,
			"versionNonce": 1463644879,
			"isDeleted": false,
			"id": "fGhSS8Yk7eusCdKdIOcE8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 515.5186871065861,
			"y": 92.54600857666415,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 136.75566425209934,
			"height": 45.9040125829718,
			"seed": 1858945134,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 140,
			"versionNonce": 1537418657,
			"isDeleted": false,
			"id": "hmDu6EheaxZI6FEYKkSX8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 503.64470542724894,
			"y": 143.1450419707346,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 86.23223052878222,
			"height": 18.04859998509906,
			"seed": 374470650,
			"groupIds": [
				"Vdu5vuIaRqePFBQ1gyNtC",
				"PpzRvXaUM2bPlnMsvInt1"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 144,
			"versionNonce": 2143568111,
			"isDeleted": false,
			"id": "0Iyvs71R",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 507.04136339134277,
			"y": 142.41108488555517,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 82,
			"height": 20,
			"seed": 85069,
			"groupIds": [
				"Vdu5vuIaRqePFBQ1gyNtC",
				"PpzRvXaUM2bPlnMsvInt1"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "[[Carry Out]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Carry Out",
			"rawText": "Carry Out",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Carry Out"
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 2119158145,
			"isDeleted": false,
			"id": "5kPAwW17",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 597.6475382435958,
			"y": 143.81887005307317,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 29,
			"height": 40,
			"seed": 1350504038,
			"groupIds": [
				"PpzRvXaUM2bPlnMsvInt1"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "sum\n",
			"rawText": "sum\n",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sum\n"
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 646728463,
			"isDeleted": false,
			"id": "xrUVCiRK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 507.12448467893626,
			"y": 163.54824217061469,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 123,
			"height": 40,
			"seed": 88714086,
			"groupIds": [
				"PpzRvXaUM2bPlnMsvInt1"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "is greater than\navailible digits",
			"rawText": "is greater than\navailible digits",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "is greater than\navailible digits"
		},
		{
			"type": "rectangle",
			"version": 183,
			"versionNonce": 259846497,
			"isDeleted": false,
			"id": "0KbjU3LmuKzQnH2-iGRcf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 503.6428372863626,
			"y": 143.19499662270212,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 129.40157488445357,
			"height": 62.08954082990934,
			"seed": 2084518970,
			"groupIds": [
				"PpzRvXaUM2bPlnMsvInt1"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 131,
			"versionNonce": 1745752367,
			"isDeleted": false,
			"id": "6to7iCUltGWqPXG2f4dg4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 142.02632651981224,
			"y": 306.95264086375744,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 74.38763924626488,
			"height": 19.352881567561326,
			"seed": 392513914,
			"groupIds": [
				"N9Gg-54ryHAGnqf0DYk2v",
				"9PlP3qnwkwCg3G2YRh7kc"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 131,
			"versionNonce": 1954159937,
			"isDeleted": false,
			"id": "mu0yWaws",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 145.65585555382287,
			"y": 307.00784072356646,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 68,
			"height": 20,
			"seed": 88687,
			"groupIds": [
				"N9Gg-54ryHAGnqf0DYk2v",
				"9PlP3qnwkwCg3G2YRh7kc"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "[[Overflow]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Overflow",
			"rawText": "Overflow",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Overflow"
		},
		{
			"type": "text",
			"version": 31,
			"versionNonce": 1035080527,
			"isDeleted": false,
			"id": "LkLENFme",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 221.25220346078785,
			"y": 310.3386064655751,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 50,
			"height": 20,
			"seed": 1483969786,
			"groupIds": [
				"9PlP3qnwkwCg3G2YRh7kc"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "sign is",
			"rawText": "sign is",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sign is"
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 1017564449,
			"isDeleted": false,
			"id": "fSi8XYOW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 145.0502135437929,
			"y": 331.5058387038666,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 84,
			"height": 40,
			"seed": 1923303398,
			"groupIds": [
				"9PlP3qnwkwCg3G2YRh7kc"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "changed by\naccident",
			"rawText": "changed by\naccident",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "changed by\naccident"
		},
		{
			"type": "rectangle",
			"version": 240,
			"versionNonce": 1607520623,
			"isDeleted": false,
			"id": "WNz_hQkeg4yAa6dOeS3OZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140.81679016656173,
			"y": 308.162177217008,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 138.49398878562886,
			"height": 64.71118692727066,
			"seed": 1401996198,
			"groupIds": [
				"9PlP3qnwkwCg3G2YRh7kc"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 148,
			"versionNonce": 1601339649,
			"isDeleted": false,
			"id": "z3F5NmmoIbq9Rh7mRy8Zl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 283.5545470957521,
			"y": 224.34575505212695,
			"strokeColor": "#d9480f",
			"backgroundColor": "#fd7e14",
			"width": 108.1197752009931,
			"height": 22.279236403700622,
			"seed": 1777371430,
			"groupIds": [
				"KKUdV8p7MtjYw2wv3N5S2"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 1739770767,
			"isDeleted": false,
			"id": "QCiAC70z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 288.48793187919114,
			"y": 226.38305822557953,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 103,
			"height": 20,
			"seed": 90973,
			"groupIds": [
				"KKUdV8p7MtjYw2wv3N5S2"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "[[Binary Codes]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Binary Codes",
			"rawText": "Binary Codes",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Binary Codes"
		},
		{
			"type": "text",
			"version": 38,
			"versionNonce": 979155169,
			"isDeleted": false,
			"id": "GiwONAMM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 399.5375586777042,
			"y": 227.9853732539773,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 99,
			"height": 20,
			"seed": 1910039270,
			"groupIds": [
				"KKUdV8p7MtjYw2wv3N5S2"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "each decimal",
			"rawText": "each decimal",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "each decimal"
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 831553967,
			"isDeleted": false,
			"id": "8yN57yve",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 286.1756425538177,
			"y": 250.2646096576779,
			"strokeColor": "#000000",
			"backgroundColor": "#fd7e14",
			"width": 215,
			"height": 80,
			"seed": 155875814,
			"groupIds": [
				"KKUdV8p7MtjYw2wv3N5S2"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "digit is represented by 4\nbinary bits. Types:\nBCD(8421), 2421, 8,4,-2,-1,\nExcess-3 (BCD + 3)",
			"rawText": "digit is represented by 4\nbinary bits. Types:\nBCD(8421), 2421, 8,4,-2,-1,\nExcess-3 (BCD + 3)",
			"baseline": 75,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "digit is represented by 4\nbinary bits. Types:\nBCD(8421), 2421, 8,4,-2,-1,\nExcess-3 (BCD + 3)"
		},
		{
			"type": "rectangle",
			"version": 194,
			"versionNonce": 1324676289,
			"isDeleted": false,
			"id": "XYSSWokwQzzNuxgssP-fN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 282.2440243633382,
			"y": 223.69049368592,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 222.79226405053123,
			"height": 109.43032293002585,
			"seed": 1389077158,
			"groupIds": [
				"KKUdV8p7MtjYw2wv3N5S2"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 180,
			"versionNonce": 2123527119,
			"isDeleted": false,
			"id": "sfuN8uYZx-tcSc3HCge8z",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 132.59386692774743,
			"y": -21.837163776766687,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 521.5327309532219,
			"height": 1.7679030665318862,
			"seed": 1123387450,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					521.5327309532219,
					-1.7679030665318862
				]
			]
		},
		{
			"type": "line",
			"version": 119,
			"versionNonce": 1088074913,
			"isDeleted": false,
			"id": "hJCIUzBOcYOVb8WZvgFPk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 653.5373493123755,
			"y": -23.605044363191325,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 0.5892485685940301,
			"height": 162.0581707539449,
			"seed": 1573275174,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.5892485685940301,
					162.0581707539449
				]
			]
		},
		{
			"type": "line",
			"version": 34,
			"versionNonce": 1456546287,
			"isDeleted": false,
			"id": "rsig42gQrbUbQKioKcRha",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 654.715936369992,
			"y": 139.04246487977608,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 20.036339661194575,
			"height": 0,
			"seed": 2021166650,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-20.036339661194575,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 79,
			"versionNonce": 331184257,
			"isDeleted": false,
			"id": "B8GC-KGQSSg6441b2S1ZM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633.501009651181,
			"y": 139.04246487977608,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 0.5892485685939164,
			"height": 68.35908342668455,
			"seed": 59960762,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.5892485685939164,
					68.35908342668455
				]
			]
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 726993935,
			"isDeleted": false,
			"id": "kS8uh6dYfDC_QaNsmnoAU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 634.090348140204,
			"y": 207.99079687505485,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 127.87862904060262,
			"height": 0,
			"seed": 622086886,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-127.87862904060262,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 105,
			"versionNonce": 693944417,
			"isDeleted": false,
			"id": "0I2Cwy7-QnbKjYmp0sZ4d",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 506.80105758862464,
			"y": 208.5801353640776,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 0.5892485685939164,
			"height": 123.1641908897081,
			"seed": 427072806,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.5892485685939164,
					123.1641908897081
				]
			]
		},
		{
			"type": "line",
			"version": 153,
			"versionNonce": 941011503,
			"isDeleted": false,
			"id": "9hj4Iwt_2xkBaLXAgZRh1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 507.9796446462411,
			"y": 335.28017734706367,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 228.0601475057179,
			"height": 1.7678805864247238,
			"seed": 492095994,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-228.0601475057179,
					1.7678805864247238
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 2139622465,
			"isDeleted": false,
			"id": "VIMoSdGTHf2jRXaTDygH7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.6874226871622,
			"y": 338.2266449911049,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 37.12607679770491,
			"seed": 1037357798,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					37.12607679770491
				]
			]
		},
		{
			"type": "line",
			"version": 139,
			"versionNonce": 637441103,
			"isDeleted": false,
			"id": "N22RfH8Y-tyKtMb476LXC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 281.6874226871622,
			"y": 375.94201531761803,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 315.8661871443601,
			"height": 0.5892935288082413,
			"seed": 438141158,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-315.8661871443601,
					0.5892935288082413
				]
			]
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 773774369,
			"isDeleted": false,
			"id": "HVbVoKhpBIDxcsDdj4pQg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -34.178854377626394,
			"y": 35.325129041543846,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 166.77263138494652,
			"height": 0.5892935288082413,
			"seed": 577246246,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					166.77263138494652,
					0.5892935288082413
				]
			]
		},
		{
			"type": "line",
			"version": 75,
			"versionNonce": 1826959983,
			"isDeleted": false,
			"id": "ODtndB3WqDHKKNPCQaop5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 133.18302557591406,
			"y": 35.91442257035209,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 1.1786769780450754,
			"height": 57.16232653847081,
			"seed": 1921194918,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.1786769780450754,
					-57.16232653847081
				]
			]
		},
		{
			"type": "rectangle",
			"version": 624,
			"versionNonce": 621850625,
			"isDeleted": false,
			"id": "riFdxNkDjKekjYU6i2kN7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 341.15125314607855,
			"y": -306.8200820909055,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 139.29414636948528,
			"height": 26.352933995863964,
			"seed": 465739558,
			"groupIds": [
				"TsqG9OxtL7v4gTYF9F_Pt"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 663,
			"versionNonce": 1972571279,
			"isDeleted": false,
			"id": "seKftyGB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 347.74780682224633,
			"y": -305.4209573722489,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 128,
			"height": 25,
			"seed": 670051002,
			"groupIds": [
				"TsqG9OxtL7v4gTYF9F_Pt"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 2: Logic",
			"rawText": "Unit 2: Logic",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 2: Logic"
		},
		{
			"type": "rectangle",
			"version": 587,
			"versionNonce": 710739937,
			"isDeleted": false,
			"id": "aD1XSeu9Qr1QyavQuBDEl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -112.95376655796835,
			"y": -165.5887944276779,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 138.66674804687497,
			"height": 27.733317057291686,
			"seed": 855698554,
			"groupIds": [
				"4gk2BSQGM0DmYHFVcWdwM",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 621,
			"versionNonce": 2076222127,
			"isDeleted": false,
			"id": "pRDkZ99r",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -105.13109090191855,
			"y": -162.22060202742682,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 127,
			"height": 20,
			"seed": 79309,
			"groupIds": [
				"4gk2BSQGM0DmYHFVcWdwM",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": "[[Boolean Algebra]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Boolean Algebra",
			"rawText": "Boolean Algebra",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Boolean Algebra"
		},
		{
			"type": "image",
			"version": 471,
			"versionNonce": 403923905,
			"isDeleted": false,
			"id": "4l2rhIYi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 35.7460348695229,
			"y": -157.27493413973608,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51,
			"height": 14,
			"seed": 42673,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5dae4e5c4d8a7919e3ffd7b9aed6fc3b92c1c573",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 377,
			"versionNonce": 806778063,
			"isDeleted": false,
			"id": "72anB4cq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 92.77935553428529,
			"y": -163.07982779557494,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 35,
			"height": 20,
			"seed": 735881894,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "AND",
			"rawText": "AND",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "AND"
		},
		{
			"type": "image",
			"version": 461,
			"versionNonce": 1515406241,
			"isDeleted": false,
			"id": "vQ2TeoAg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -110.54788949880762,
			"y": -132.49046168427412,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 41,
			"height": 14,
			"seed": 23022,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "4bf7763a53ba16deac1887eec231422ddc852901",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 374,
			"versionNonce": 439157487,
			"isDeleted": false,
			"id": "FnasmEY6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -65.62551872493404,
			"y": -133.35757999460205,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 43,
			"height": 20,
			"seed": 654278054,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "= OR",
			"rawText": "= OR",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "= OR"
		},
		{
			"type": "image",
			"version": 625,
			"versionNonce": 759965569,
			"isDeleted": false,
			"id": "C9sf6p1a",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 30.344454991879303,
			"y": -93.8488251920466,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29,
			"height": 14,
			"seed": 26808,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "f579a537316853914bb0854b3b681ff27e426d34",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 516,
			"versionNonce": 982306063,
			"isDeleted": false,
			"id": "3IiO0etz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 69.6700071577275,
			"y": -96.58713829159166,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 37,
			"height": 20,
			"seed": 2051788966,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "NOT",
			"rawText": "NOT",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NOT"
		},
		{
			"type": "line",
			"version": 892,
			"versionNonce": 457019233,
			"isDeleted": false,
			"id": "1742xIGLOvg0nM6Z4ygjZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 95.00966948689029,
			"y": -120.34602005969964,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.481320566770588,
			"height": 0,
			"seed": 2110603494,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					21.481320566770588,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 902,
			"versionNonce": 1823363887,
			"isDeleted": false,
			"id": "oSO1LQg92h5kWMdcUTz-E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 37.72614797550207,
			"y": -127.50646024862317,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.64176075569412,
			"height": 0,
			"seed": 427832358,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					28.64176075569412,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 904,
			"versionNonce": 980876097,
			"isDeleted": false,
			"id": "fhp-gUMgUhObT0FgsDWAt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 37.72614797550207,
			"y": -113.18557987077614,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.64176075569412,
			"height": 0,
			"seed": 15908710,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					28.64176075569412,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 955,
			"versionNonce": 150607183,
			"isDeleted": false,
			"id": "qXTHyx8fVMEMRCVoQEeaV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 66.3679087311962,
			"y": -134.66690043754673,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 28.64176075569412,
			"seed": 1215423142,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					28.64176075569412
				]
			]
		},
		{
			"type": "line",
			"version": 1018,
			"versionNonce": 727182113,
			"isDeleted": false,
			"id": "_CzweItW-cCfoaHewOZY7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 66.3679087311962,
			"y": -134.66690043754673,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.32088037784706,
			"height": 0,
			"seed": 1923784166,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.32088037784706,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 960,
			"versionNonce": 1187550063,
			"isDeleted": false,
			"id": "IW498hbVhvpoYxiASen0E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 66.3679087311962,
			"y": -106.02513968185258,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.32088037784706,
			"height": 0,
			"seed": 615117094,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.32088037784706,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1687,
			"versionNonce": 1448075009,
			"isDeleted": false,
			"id": "7Ysmdq3aJwmtZJFVeWKch",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 80.68878910904323,
			"y": -134.66690043754673,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.68271406412017,
			"height": 28.64176075569412,
			"seed": 1507646566,
			"groupIds": [
				"zT8wSngX8569fgpDfU5Gs",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.364151541761986,
					2.820769146151195
				],
				[
					13.68271406412017,
					14.844195522054143
				],
				[
					9.585541593096732,
					26.076260705848902
				],
				[
					0,
					28.64176075569412
				]
			]
		},
		{
			"type": "line",
			"version": 795,
			"versionNonce": 1583500687,
			"isDeleted": false,
			"id": "QOjEu_H08q1LZXketX_GF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -36.21255068533637,
			"y": -91.42791615902613,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.89923705826935,
			"height": 0,
			"seed": 240696038,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.89923705826935,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 945,
			"versionNonce": 1776178913,
			"isDeleted": false,
			"id": "6yz_ReLK_d_ymeDv49E7V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -102.61051617405471,
			"y": -99.7276618451159,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.61021516082427,
			"height": 0.07621670316101606,
			"seed": 1049390630,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					38.61021516082427,
					-0.07621670316101606
				]
			]
		},
		{
			"type": "line",
			"version": 852,
			"versionNonce": 1795146671,
			"isDeleted": false,
			"id": "LoW44ruXcOrZbXwUsLAWD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -102.61051617405471,
			"y": -83.12817047293635,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.7626332163501,
			"height": 0.0762167031609217,
			"seed": 1818736998,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					38.7626332163501,
					-0.0762167031609217
				]
			]
		},
		{
			"type": "line",
			"version": 867,
			"versionNonce": 412275393,
			"isDeleted": false,
			"id": "luhrEVtemwWVkd6toku6Z",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -69.41153342969548,
			"y": -108.02740753120571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.299745686089784,
			"height": 33.198982744359135,
			"seed": 792173734,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.299745686089784,
					16.599491372179568
				],
				[
					0,
					33.198982744359135
				]
			]
		},
		{
			"type": "line",
			"version": 943,
			"versionNonce": 214529487,
			"isDeleted": false,
			"id": "AUKycvE7a7yrVg5zkXYrm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -69.41153342969548,
			"y": -108.02740753120571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.198982744359135,
			"height": 16.599491372179568,
			"seed": 749279206,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.228279173257384,
					1.6767252548512468
				],
				[
					33.198982744359135,
					16.599491372179568
				]
			]
		},
		{
			"type": "line",
			"version": 880,
			"versionNonce": 386716321,
			"isDeleted": false,
			"id": "dzyF1HfX5JqHItxqH2-Bg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -69.41153342969548,
			"y": -74.82842478684655,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.198982744359135,
			"height": 16.599491372179568,
			"seed": 1288252198,
			"groupIds": [
				"cXbFG48lxjArow4Uz-cr4",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.389916545831714,
					-2.0958960148917063
				],
				[
					33.198982744359135,
					-16.599491372179568
				]
			]
		},
		{
			"type": "line",
			"version": 693,
			"versionNonce": 1255662575,
			"isDeleted": false,
			"id": "BOAhCxEROW15X7Ae7p64_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 37.13451177617938,
			"y": -63.28827628381811,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.564056728477468,
			"height": 0,
			"seed": 1385855206,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.564056728477468,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 690,
			"versionNonce": 1509676673,
			"isDeleted": false,
			"id": "lT7nE_-tBSAAPtSdCDuc-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 61.69856850465683,
			"y": -75.57030464805683,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 24.564056728477468,
			"seed": 1340501030,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					24.564056728477468
				]
			]
		},
		{
			"type": "line",
			"version": 774,
			"versionNonce": 892571151,
			"isDeleted": false,
			"id": "74kiNulHVLvMEzR4_9U6q",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 61.69856850465683,
			"y": -75.57030464805683,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.564056728477468,
			"height": 12.282028364238734,
			"seed": 2110912358,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347336,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.564056728477468,
					12.282028364238734
				]
			]
		},
		{
			"type": "line",
			"version": 695,
			"versionNonce": 337600097,
			"isDeleted": false,
			"id": "nRQa-Mm5XB4U82qOvwFNT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 61.81969060018767,
			"y": -50.97498793342271,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.564056728477468,
			"height": 12.282028364238734,
			"seed": 1420434086,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.564056728477468,
					-12.282028364238734
				]
			]
		},
		{
			"type": "line",
			"version": 757,
			"versionNonce": 1188361263,
			"isDeleted": false,
			"id": "cndErHNpt0s4MAazPtKtA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 92.29085334379351,
			"y": -63.28827628381811,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.394814435698812,
			"height": 0,
			"seed": 991679974,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.394814435698812,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 627,
			"versionNonce": 1950804545,
			"isDeleted": false,
			"id": "Ni7NhJpPdMOhhzn1JcPMU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": 86.39256625421285,
			"y": -66.11605628233907,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.655559997041878,
			"height": 5.655559997041878,
			"seed": 976496934,
			"groupIds": [
				"GiiBUf8G-6tkHxFcErLro",
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 540,
			"versionNonce": 128226895,
			"isDeleted": false,
			"id": "eDsZecTMArnqRowdyCJx_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -114.55345745071378,
			"y": -166.85102377024708,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 244.9750650962804,
			"height": 123.11890189815455,
			"seed": 449883942,
			"groupIds": [
				"Uat_mQXXe6CPqcyXJVa6a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "image",
			"version": 138,
			"versionNonce": 592575009,
			"isDeleted": false,
			"id": "Hljv0bgw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3.568852014048204,
			"y": -94.3511117190733,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20,
			"height": 18,
			"seed": 74460,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b79d1033bb9586acb49ed5495f8aa2efc1884872",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 149,
			"versionNonce": 1853551727,
			"isDeleted": false,
			"id": "1Tzul3i4Jf5aEau17AXLm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.83391168988018,
			"y": -157.7213786712,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 83.94872479683468,
			"height": 19.865721304372812,
			"seed": 1907050022,
			"groupIds": [
				"5tA_fnJdElwdhYmTUrX2d",
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 65,
			"versionNonce": 36703745,
			"isDeleted": false,
			"id": "Ze2rDfwg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 141.15533696793017,
			"y": -158.251106835747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 79,
			"height": 20,
			"seed": 1552022182,
			"groupIds": [
				"5tA_fnJdElwdhYmTUrX2d",
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Theorems:",
			"rawText": "Theorems:",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Theorems:"
		},
		{
			"type": "image",
			"version": 154,
			"versionNonce": 52465295,
			"isDeleted": false,
			"id": "xJ156JaU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 155.17151138741212,
			"y": -132.30359315776306,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77,
			"height": 12,
			"seed": 7376,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "72ed837296f4eb2f8d314c7d1a708a79090c3c8a",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 154,
			"versionNonce": 669033953,
			"isDeleted": false,
			"id": "0XazZAaI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 154.50082034442747,
			"y": -114.50758731092654,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 68,
			"height": 12,
			"seed": 76086,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "16e2744384506a3339e82159ac4dd53c37d5442c",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 38,
			"versionNonce": 1078846639,
			"isDeleted": false,
			"id": "l2ODkkvl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 140.74474157755964,
			"y": -137.4741580273416,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 11,
			"height": 20,
			"seed": 43734138,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1.",
			"rawText": "1.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1."
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 527647169,
			"isDeleted": false,
			"id": "ofH63O5E",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 138.07391733472576,
			"y": -99.54341994669588,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 18,
			"height": 20,
			"seed": 424000486,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "2.",
			"rawText": "2.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2."
		},
		{
			"type": "image",
			"version": 154,
			"versionNonce": 900429519,
			"isDeleted": false,
			"id": "zf8y6zse",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 157.34358884494344,
			"y": -97.39953606113541,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 75,
			"height": 14,
			"seed": 62567,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "410a9090df6608f430fabb788d4cd922b02461d6",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 179,
			"versionNonce": 1711759777,
			"isDeleted": false,
			"id": "f8JFD1Ym",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 157.46183348864156,
			"y": -78.44178191660433,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66,
			"height": 14,
			"seed": 40738,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ffabaee701a8445a90eee6e5c88abe73ef374714",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 1775355119,
			"isDeleted": false,
			"id": "fkdbqoHZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 137.43278660351297,
			"y": -55.57578034698608,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 17,
			"height": 20,
			"seed": 462703526,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "3.",
			"rawText": "3.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3."
		},
		{
			"type": "image",
			"version": 172,
			"versionNonce": 684492161,
			"isDeleted": false,
			"id": "CFEcVFSx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 153.79546703573618,
			"y": -55.53223241099869,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 19,
			"seed": 49452,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e5adb72980aaae9c31cb11c8dc32b5cd22f2f5eb",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 2085179151,
			"isDeleted": false,
			"id": "iD8hkXaJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 235.87886759622668,
			"y": -155.37145153468742,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 17,
			"height": 20,
			"seed": 41652710,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "4.",
			"rawText": "4.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4."
		},
		{
			"type": "image",
			"version": 155,
			"versionNonce": 1124216161,
			"isDeleted": false,
			"id": "2n4n1MJZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 256.6030053378915,
			"y": -155.32097139889726,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 196,
			"height": 18,
			"seed": 15791,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e5f046b0c9882390696be4612258c2a953a2c3f5",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 189,
			"versionNonce": 126522671,
			"isDeleted": false,
			"id": "zepvG7El",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 256.8427654209237,
			"y": -136.77762808896418,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 160,
			"height": 18,
			"seed": 71971,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "06a42b393141efa031aebdce8561c4b076518284",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 2079840577,
			"isDeleted": false,
			"id": "nP3u6LIv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 237.28773643279712,
			"y": -116.78840550136886,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 16,
			"height": 20,
			"seed": 1122991354,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "5.",
			"rawText": "5.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5."
		},
		{
			"type": "image",
			"version": 165,
			"versionNonce": 1123948367,
			"isDeleted": false,
			"id": "bbLubSZT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 252.9508920025773,
			"y": -117.03895048192436,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 19,
			"seed": 34269,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "7fbce1202ca526e0e24fe2738d6eeeee9bbba898",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 152,
			"versionNonce": 84740385,
			"isDeleted": false,
			"id": "jT3c1r1A",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 255.2200392328553,
			"y": -94.79686291319922,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 114,
			"height": 19,
			"seed": 88919,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9c1100bdf374d59064f8fe149b4e24be2488994d",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 37,
			"versionNonce": 1694258543,
			"isDeleted": false,
			"id": "sHCzZFew",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 239.54177758067945,
			"y": -73.32824083843119,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 17,
			"height": 20,
			"seed": 563565498,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "6.",
			"rawText": "6.",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6."
		},
		{
			"type": "image",
			"version": 155,
			"versionNonce": 934362369,
			"isDeleted": false,
			"id": "jT5w3YG1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 259.88527334822044,
			"y": -69.61027556456233,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 14,
			"seed": 65635,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "9bbb89a9031545a448ee59275a133e9ca008ef4b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 177,
			"versionNonce": 1154338703,
			"isDeleted": false,
			"id": "a9YaUH0s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 259.16006298325857,
			"y": -53.97230375300168,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 100,
			"height": 18,
			"seed": 50887,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "58722e2b5e8d19b6b1e647212362150fa12cd430",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 310,
			"versionNonce": 325317857,
			"isDeleted": false,
			"id": "K8qHSISjRQFPLgGxw_9yn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 136.19309842296752,
			"y": -159.0588152897789,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 322.1481233021286,
			"height": 128.49728836953759,
			"seed": 1197763110,
			"groupIds": [
				"h7ohwEUwP8nqRtpP092LV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 456,
			"versionNonce": 1017841071,
			"isDeleted": false,
			"id": "GHJJ07Ip4PKHnxFhxMYk7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 463.5731179197837,
			"y": -89.90339594131981,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 169.49002239964273,
			"height": 19.461275438465265,
			"seed": 1674034682,
			"groupIds": [
				"9fwaM9yeH_ELUEvTPx2n9",
				"CqQmRnhYLdPr1gqVBtueT"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 310,
			"versionNonce": 2075439297,
			"isDeleted": false,
			"id": "CDs6CUWC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 467.4241428918159,
			"y": -90.72015438105089,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 166,
			"height": 20,
			"seed": 695942010,
			"groupIds": [
				"9fwaM9yeH_ELUEvTPx2n9",
				"CqQmRnhYLdPr1gqVBtueT"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Operator Precedence",
			"rawText": "Operator Precedence",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Operator Precedence"
		},
		{
			"type": "text",
			"version": 318,
			"versionNonce": 1270642639,
			"isDeleted": false,
			"id": "OCZcWvGM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 466.0500237186155,
			"y": -71.21912904310298,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 164,
			"height": 40,
			"seed": 510050534,
			"groupIds": [
				"CqQmRnhYLdPr1gqVBtueT"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Parantheses -> NOT\n-> AND -> OR",
			"rawText": "Parantheses -> NOT\n-> AND -> OR",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Parantheses -> NOT\n-> AND -> OR"
		},
		{
			"type": "rectangle",
			"version": 494,
			"versionNonce": 910356641,
			"isDeleted": false,
			"id": "hPJiM8_GiYKD-aXF8aEff",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 463.2192819473661,
			"y": -90.96491735654976,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 171.25925625363925,
			"height": 61.214554588667994,
			"seed": 151049530,
			"groupIds": [
				"CqQmRnhYLdPr1gqVBtueT"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 388,
			"versionNonce": 2015012335,
			"isDeleted": false,
			"id": "RxgMBJPHNDX6cheknI83W",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 466.26886504527783,
			"y": -269.1504370758855,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 148.55960098628782,
			"height": 22.79483957947764,
			"seed": 1121049018,
			"groupIds": [
				"_ZfgR4PBRFT0g9fboHkgA",
				"iF_gA_QH270C7b5_xBzz6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 412,
			"versionNonce": 683553921,
			"isDeleted": false,
			"id": "AJd1eFxH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 471.19465497442854,
			"y": -266.8244385047274,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 142,
			"height": 20,
			"seed": 70622,
			"groupIds": [
				"_ZfgR4PBRFT0g9fboHkgA",
				"iF_gA_QH270C7b5_xBzz6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": "[[Boolean Functions]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Boolean Functions",
			"rawText": "Boolean Functions",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Boolean Functions"
		},
		{
			"type": "text",
			"version": 384,
			"versionNonce": 1892552719,
			"isDeleted": false,
			"id": "6pPWoABF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 468.39254148669846,
			"y": -242.65447275764802,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 147,
			"height": 100,
			"seed": 1888862330,
			"groupIds": [
				"iF_gA_QH270C7b5_xBzz6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "function formed w/\nbinary variables, \nbinary operators, \nParantheses\n(ouput/input 0or1)",
			"rawText": "function formed w/\nbinary variables, \nbinary operators, \nParantheses\n(ouput/input 0or1)",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "function formed w/\nbinary variables, \nbinary operators, \nParantheses\n(ouput/input 0or1)"
		},
		{
			"type": "rectangle",
			"version": 354,
			"versionNonce": 1457912929,
			"isDeleted": false,
			"id": "X6mVOVRgVpP5M-akhzcEs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 465.11643186082074,
			"y": -244.86369652225716,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 151.14070179882503,
			"height": 147.10833660515556,
			"seed": 2052420282,
			"groupIds": [
				"iF_gA_QH270C7b5_xBzz6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 1875850799,
			"isDeleted": false,
			"id": "QBdFWx21",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 468.32657418289756,
			"y": -139.59883160252596,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 147,
			"height": 40,
			"seed": 710495674,
			"groupIds": [
				"iF_gA_QH270C7b5_xBzz6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "2 forms: standard\nand canonical",
			"rawText": "2 forms: standard\nand canonical",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2 forms: standard\nand canonical"
		},
		{
			"type": "rectangle",
			"version": 190,
			"versionNonce": 545900609,
			"isDeleted": false,
			"id": "onUsYUA6wNtJkkhKHPxdc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 307.33481933192274,
			"y": -269.877350802238,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 151.30408775624662,
			"height": 22.03458567967948,
			"seed": 308472634,
			"groupIds": [
				"IUOpKTpuhBu7kPeR2_6-a",
				"dTtNwDlqmDJx8Djr99cog"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1543936079,
			"isDeleted": false,
			"id": "9ORaLW8M",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 312.61063985466285,
			"y": -268.6099629820967,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 144,
			"height": 20,
			"seed": 1978788262,
			"groupIds": [
				"IUOpKTpuhBu7kPeR2_6-a",
				"dTtNwDlqmDJx8Djr99cog"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Canonical Function",
			"rawText": "Canonical Function",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Canonical Function"
		},
		{
			"type": "text",
			"version": 35,
			"versionNonce": 1065949217,
			"isDeleted": false,
			"id": "2LVMPvEP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 309.6043190883596,
			"y": -243.31948836851961,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 107,
			"height": 40,
			"seed": 581921466,
			"groupIds": [
				"dTtNwDlqmDJx8Djr99cog"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(SOP) Sum of\nMinterms",
			"rawText": "(SOP) Sum of\nMinterms",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(SOP) Sum of\nMinterms"
		},
		{
			"type": "text",
			"version": 35,
			"versionNonce": 726447727,
			"isDeleted": false,
			"id": "lnyDwUWg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 312.32466476633783,
			"y": -199.79330893001946,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 143,
			"height": 40,
			"seed": 2034912486,
			"groupIds": [
				"dTtNwDlqmDJx8Djr99cog"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(POS) sum of max\nterms",
			"rawText": "(POS) sum of max\nterms",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(POS) sum of max\nterms"
		},
		{
			"type": "rectangle",
			"version": 273,
			"versionNonce": 97741825,
			"isDeleted": false,
			"id": "TVYvquRArTB6Bn9RR1kMO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 306.4234550160155,
			"y": -271.3669045802493,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 152.93010099758806,
			"height": 109.44061081867443,
			"seed": 594556282,
			"groupIds": [
				"dTtNwDlqmDJx8Djr99cog"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 213,
			"versionNonce": 74059919,
			"isDeleted": false,
			"id": "03D3TtX9tqkxRlDEJ9fpT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 151.50551785405554,
			"y": -269.91644254649145,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 148.98134532304942,
			"height": 21.660422798514418,
			"seed": 916427450,
			"groupIds": [
				"zenwtEg_DITTpbMORaecy",
				"v0yQP5cwcSaN0TLvbDZnw"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 38,
			"versionNonce": 1533559777,
			"isDeleted": false,
			"id": "RV1oAVFr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 154.4224524307628,
			"y": -269.7993543015079,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 145,
			"height": 20,
			"seed": 933257978,
			"groupIds": [
				"zenwtEg_DITTpbMORaecy",
				"v0yQP5cwcSaN0TLvbDZnw"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Standard Function",
			"rawText": "Standard Function",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Standard Function"
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 555165359,
			"isDeleted": false,
			"id": "ACQeUnJp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 152.4979664970165,
			"y": -245.20546943729096,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 147,
			"height": 80,
			"seed": 1978138170,
			"groupIds": [
				"v0yQP5cwcSaN0TLvbDZnw"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(SOP) Sum of \nProducts: xy + z'y\n(POS) Product of\nSums: (x+y)(z'+y)",
			"rawText": "(SOP) Sum of \nProducts: xy + z'y\n(POS) Product of\nSums: (x+y)(z'+y)",
			"baseline": 75,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(SOP) Sum of \nProducts: xy + z'y\n(POS) Product of\nSums: (x+y)(z'+y)"
		},
		{
			"type": "rectangle",
			"version": 242,
			"versionNonce": 2086084545,
			"isDeleted": false,
			"id": "k_Ry7BrNMGG1qXIDrZCSY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.5334835222589,
			"y": -269.92299322087877,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 150.8722984565099,
			"height": 106.47497123673566,
			"seed": 1514938746,
			"groupIds": [
				"v0yQP5cwcSaN0TLvbDZnw"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 224,
			"versionNonce": 1878816975,
			"isDeleted": false,
			"id": "GFgmUOlhfWLS1ChP-QHWL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -29.80541416842992,
			"y": -253.76626532883648,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 45.36406274143731,
			"height": 16.879658271970612,
			"seed": 1884718502,
			"groupIds": [
				"pH8_VvYbp7Lq2obh5JtSy",
				"_cR5BI3OyKEGASzD85KHQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 1992261537,
			"isDeleted": false,
			"id": "uOaPUvT9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -26.028071018003857,
			"y": -255.7699910425511,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 39,
			"height": 20,
			"seed": 844140198,
			"groupIds": [
				"pH8_VvYbp7Lq2obh5JtSy",
				"_cR5BI3OyKEGASzD85KHQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Cost",
			"rawText": "Cost",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Cost"
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 1991411439,
			"isDeleted": false,
			"id": "8t7mUZeJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 21.258733789733668,
			"y": -257.2784390782501,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 58,
			"height": 40,
			"seed": 951901562,
			"groupIds": [
				"_cR5BI3OyKEGASzD85KHQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "sum of:\n",
			"rawText": "sum of:\n",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sum of:\n"
		},
		{
			"type": "text",
			"version": 177,
			"versionNonce": 1758520193,
			"isDeleted": false,
			"id": "IObAPv2Z",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -29.225615287179792,
			"y": -233.71229673741516,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 171,
			"height": 60,
			"seed": 31128058,
			"groupIds": [
				"_cR5BI3OyKEGASzD85KHQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "# of inputs\nLogic Gates\nInternal Connecttions",
			"rawText": "# of inputs\nLogic Gates\nInternal Connecttions",
			"baseline": 55,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "# of inputs\nLogic Gates\nInternal Connecttions"
		},
		{
			"type": "rectangle",
			"version": 315,
			"versionNonce": 1942081807,
			"isDeleted": false,
			"id": "fnWDPOyH6P9JCowlBuAdR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.327783056745027,
			"y": -254.36982813584495,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 176.33960902054912,
			"height": 82.21620028907074,
			"seed": 368431078,
			"groupIds": [
				"_cR5BI3OyKEGASzD85KHQ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 2388,
			"versionNonce": 2127219553,
			"isDeleted": false,
			"id": "-n7l16i0LAOiwxYqI_irF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 299.87640562694304,
			"y": 147.96290866924693,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.87614698084813,
			"height": 21.05530936180881,
			"seed": 1182260538,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 2452,
			"versionNonce": 1084413743,
			"isDeleted": false,
			"id": "PXUBWXj_uGgcwMKCqR99I",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 310.01304900327955,
			"y": 168.90152182985707,
			"strokeColor": "#000000",
			"backgroundColor": "#ced4da",
			"width": 1.1224928380901291,
			"height": 25.526001257026532,
			"seed": 1018963450,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.1224928380901291,
					25.526001257026532
				]
			]
		},
		{
			"type": "line",
			"version": 2405,
			"versionNonce": 821868353,
			"isDeleted": false,
			"id": "9HR6qJX7xKkD7HJOOnQCb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 308.9906770733691,
			"y": 195.08126697430743,
			"strokeColor": "#000000",
			"backgroundColor": "#ced4da",
			"width": 10.104577704715853,
			"height": 15.567090561833803,
			"seed": 486102714,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.104577704715853,
					15.567090561833803
				]
			]
		},
		{
			"type": "line",
			"version": 2424,
			"versionNonce": 1941838159,
			"isDeleted": false,
			"id": "_TK7TlVS7SRjDjXTIz9UJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 308.4744202876385,
			"y": 194.54893641193988,
			"strokeColor": "#000000",
			"backgroundColor": "#ced4da",
			"width": 9.567246725226047,
			"height": 13.986228250151607,
			"seed": 131231610,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-9.567246725226047,
					13.986228250151607
				]
			]
		},
		{
			"type": "line",
			"version": 2443,
			"versionNonce": 1103505185,
			"isDeleted": false,
			"id": "zhDrZsxRTzTYzYMobLlKo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 296.0584415538782,
			"y": 183.4064711146504,
			"strokeColor": "#000000",
			"backgroundColor": "#ced4da",
			"width": 13.359528218399419,
			"height": 8.556708683848266,
			"seed": 294285370,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.359528218399419,
					-8.556708683848266
				]
			]
		},
		{
			"type": "line",
			"version": 2519,
			"versionNonce": 1114380143,
			"isDeleted": false,
			"id": "cO6GFq_pO5vTk4h5igCYP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 310.17174295540747,
			"y": 175.0981491147417,
			"strokeColor": "#000000",
			"backgroundColor": "#ced4da",
			"width": 8.486058420902676,
			"height": 10.648661407225251,
			"seed": 1308907770,
			"groupIds": [
				"UmyqoEZagUlMja7NxJ5Oy"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.486058420902676,
					10.648661407225251
				]
			]
		},
		{
			"type": "rectangle",
			"version": 319,
			"versionNonce": 2073467649,
			"isDeleted": false,
			"id": "fXeDzL6QJWaKF50QOcoja",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -52.22980735795667,
			"y": -353.3085303042527,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 75.35625695150557,
			"height": 22.279211407081846,
			"seed": 1748208038,
			"groupIds": [
				"lg-hFC8wp1kyOoP2WpPzv",
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 361,
			"versionNonce": 586502543,
			"isDeleted": false,
			"id": "DXWrCl6T",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -47.96076593699877,
			"y": -352.62972019392345,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 20,
			"seed": 57358,
			"groupIds": [
				"lg-hFC8wp1kyOoP2WpPzv",
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": "[[Minterms]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Minterms",
			"rawText": "Minterms",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Minterms"
		},
		{
			"type": "text",
			"version": 115,
			"versionNonce": 787321569,
			"isDeleted": false,
			"id": "0iuJZz6j",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -43.17238415751732,
			"y": -329.11003858491677,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 59,
			"height": 20,
			"seed": 1957742458,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x  y  z",
			"rawText": "x  y  z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x  y  z"
		},
		{
			"type": "text",
			"version": 130,
			"versionNonce": 781338543,
			"isDeleted": false,
			"id": "pk9VR3wD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -45.027941882782514,
			"y": -307.85772233418635,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 60,
			"height": 20,
			"seed": 1344461626,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0  0  1",
			"rawText": "0  0  1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0  0  1"
		},
		{
			"type": "line",
			"version": 230,
			"versionNonce": 1884982977,
			"isDeleted": false,
			"id": "2POYNdGGMsajVc9_acM_F",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 19.67869201271334,
			"y": -324.6227068309848,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 0.6740169908707685,
			"height": 59.31439512012946,
			"seed": 1203726246,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.6740169908707685,
					59.31439512012946
				]
			]
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 1131117007,
			"isDeleted": false,
			"id": "4G4lBjO9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 35.855356914612315,
			"y": -352.3435251023085,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 106,
			"height": 40,
			"seed": 291914810,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "what makes\nit = 1   name",
			"rawText": "what makes\nit = 1   name",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "what makes\nit = 1   name"
		},
		{
			"type": "image",
			"version": 222,
			"versionNonce": 377294497,
			"isDeleted": false,
			"id": "v30ibdA8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 28.779860286275067,
			"y": -307.42600053522415,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54,
			"height": 16,
			"seed": 31902,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "b4fd9a337a9c3fb868968c50bd4f589a0ad0eb02",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 210,
			"versionNonce": 1721329647,
			"isDeleted": false,
			"id": "XqBAjf3B6wHfUTq4cbS2Q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 93.18458406557701,
			"y": -326.2635991519381,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 2.4263609422217485,
			"height": 63.0856621739494,
			"seed": 1561003174,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.4263609422217485,
					63.0856621739494
				]
			]
		},
		{
			"type": "text",
			"version": 126,
			"versionNonce": 2013565569,
			"isDeleted": false,
			"id": "2cHZcyKA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 106.00968009506485,
			"y": -308.11338064761185,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 16,
			"height": 20,
			"seed": 87579302,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "enTsIKFK2-IvUi1-AqSGZ",
					"type": "arrow"
				}
			],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "m1",
			"rawText": "m1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "m1"
		},
		{
			"type": "ellipse",
			"version": 251,
			"versionNonce": 1713672719,
			"isDeleted": false,
			"id": "bir4noeisAnSST8aarc0H",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -52.290570827672255,
			"y": -310.40799465029437,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 72.40119918961624,
			"height": 24.991277945126228,
			"seed": 1065900518,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "enTsIKFK2-IvUi1-AqSGZ",
					"type": "arrow"
				}
			],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 162,
			"versionNonce": 1773181537,
			"isDeleted": false,
			"id": "M8MwhSCONawxIcMrYDzye",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 113.09290471765993,
			"y": -307.1003195314955,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 15.435779835112925,
			"height": 17.27338802756975,
			"seed": 1148171642,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "enTsIKFK2-IvUi1-AqSGZ",
					"type": "arrow"
				}
			],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 493,
			"versionNonce": 990214191,
			"isDeleted": false,
			"id": "enTsIKFK2-IvUi1-AqSGZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 11.657711991081896,
			"y": -308.60350115119184,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 85.17525362486242,
			"height": 3.9731750650287263,
			"seed": 1555996070,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6HbPfbdU4X1dhzO0duTpy",
				"focus": -1.1793466446412388,
				"gap": 2.0977597722500025
			},
			"endBinding": {
				"elementId": "ei-HmV0AC8qfRvxX36V_4",
				"focus": 1.2355711473888724,
				"gap": 12.4329924045713
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					41.335663702285146,
					-3.9731750650287263
				],
				[
					85.17525362486242,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 172,
			"versionNonce": 2085660225,
			"isDeleted": false,
			"id": "HM-Myg74ZfgKK4InxDL2a",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -48.134519259480044,
			"y": -308.04246216228506,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 20.004527561205382,
			"height": 20.00452756120535,
			"seed": 521387046,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347337,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 194,
			"versionNonce": 723819087,
			"isDeleted": false,
			"id": "0gOSd3vAgIPvlW4YYoOP0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 22.992658443244046,
			"y": -311.00612047468707,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 22.968143478498966,
			"height": 22.227246565026974,
			"seed": 450185062,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 162,
			"versionNonce": 2059679265,
			"isDeleted": false,
			"id": "XFGFv-Rph6p-aRaf9Ocvb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -20.350432789790773,
			"y": -307.30156524881306,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 16.670434923770223,
			"height": 22.597709153465757,
			"seed": 1759594918,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 168,
			"versionNonce": 727349359,
			"isDeleted": false,
			"id": "-kWwgwvQpl9Ve9fBPm6bb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 48.18354918897015,
			"y": -309.52428425263463,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 18.89318219099738,
			"height": 21.85678397658819,
			"seed": 18724006,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 164,
			"versionNonce": 670747137,
			"isDeleted": false,
			"id": "6HbPfbdU4X1dhzO0duTpy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1.1358885983586262,
			"y": -306.56065420363825,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 18.89318219099738,
			"height": 21.115901194819003,
			"seed": 427522042,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "enTsIKFK2-IvUi1-AqSGZ",
					"type": "arrow"
				}
			],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 148,
			"versionNonce": 24089231,
			"isDeleted": false,
			"id": "ei-HmV0AC8qfRvxX36V_4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 74.11533684816828,
			"y": -307.67201370554903,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 12.595473636268622,
			"height": 20.37499014964419,
			"seed": 1531283366,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "enTsIKFK2-IvUi1-AqSGZ",
					"type": "arrow"
				}
			],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1022616033,
			"isDeleted": false,
			"id": "p7abdrqO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -40.84392310940731,
			"y": -281.88221655839766,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54,
			"height": 20,
			"seed": 1668183014,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1  0  1",
			"rawText": "1  0  1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1  0  1"
		},
		{
			"type": "image",
			"version": 206,
			"versionNonce": 639396015,
			"isDeleted": false,
			"id": "2o8zPh8G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 27.349497221903704,
			"y": -280.75753231740623,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 54,
			"height": 16,
			"seed": 90891,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8b0fb5e5dbe9f0787efa239434691a09a7256458",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 650051009,
			"isDeleted": false,
			"id": "vwlMdQbC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 106.72335853627814,
			"y": -282.9571532581142,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 1637893094,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "m5",
			"rawText": "m5",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "m5"
		},
		{
			"type": "rectangle",
			"version": 366,
			"versionNonce": 1728674511,
			"isDeleted": false,
			"id": "s7fYFWIAoM2dB2mEshLZq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -54.5462341793542,
			"y": -354.91193142634665,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 199.81690359118346,
			"height": 92.43499325839826,
			"seed": 1154202726,
			"groupIds": [
				"VD6hpXiQOzSOKHrWpR_wn"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 202,
			"versionNonce": 75210145,
			"isDeleted": false,
			"id": "D4laIfQyy-qQRDsxjmXFZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 151.5850454625311,
			"y": -364.4039804033545,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 81.56301427307938,
			"height": 20.16166479611826,
			"seed": 1068497446,
			"groupIds": [
				"dznJYuvhmPKFxR0koswI8",
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 195,
			"versionNonce": 1221544175,
			"isDeleted": false,
			"id": "p0Mh8Uld",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 155.42953852083136,
			"y": -364.1197270286565,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 78,
			"height": 20,
			"seed": 69050,
			"groupIds": [
				"dznJYuvhmPKFxR0koswI8",
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": "[[Maxterms]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Maxterms",
			"rawText": "Maxterms",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Maxterms"
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1700348289,
			"isDeleted": false,
			"id": "iK1w3I6e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 242.18369012402258,
			"y": -362.6979589373799,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 67,
			"height": 20,
			"seed": 1306417914,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "same as",
			"rawText": "same as",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "same as"
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 687231759,
			"isDeleted": false,
			"id": "uhxod1AG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 154.69320076522374,
			"y": -338.4867366447899,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 178,
			"height": 40,
			"seed": 149175994,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "minterms just = 0 and\naddition",
			"rawText": "minterms just = 0 and\naddition",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "minterms just = 0 and\naddition"
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 1184328033,
			"isDeleted": false,
			"id": "8t9F9wk7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 156.475129968169,
			"y": -295.8423820979026,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 38,
			"height": 20,
			"seed": 1843377638,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0 1 1",
			"rawText": "0 1 1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0 1 1"
		},
		{
			"type": "line",
			"version": 72,
			"versionNonce": 536287535,
			"isDeleted": false,
			"id": "DJkpk7pAAlKdaOJikuiYn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 201.87863050023378,
			"y": -299.4868808321478,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 0.41272130652220085,
			"height": 21.87622892543834,
			"seed": 1758695782,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.41272130652220085,
					21.87622892543834
				]
			]
		},
		{
			"type": "image",
			"version": 165,
			"versionNonce": 1367708993,
			"isDeleted": false,
			"id": "OZcfoPw7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 207.3106912568489,
			"y": -295.2380718577807,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 72,
			"height": 16,
			"seed": 88567,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "81dd2f6cddae130a7adc8c4f6ba9a56116eb5943",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 65,
			"versionNonce": 591010639,
			"isDeleted": false,
			"id": "f_8ljTdVlQx7Knt-gyWG-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 288.2940296276495,
			"y": -299.55272567584785,
			"strokeColor": "#087f5b",
			"backgroundColor": "#12b886",
			"width": 0.5461535849455004,
			"height": 20.752565425036153,
			"seed": 849200934,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.5461535849455004,
					20.752565425036153
				]
			]
		},
		{
			"type": "text",
			"version": 41,
			"versionNonce": 1501775137,
			"isDeleted": false,
			"id": "81SjDfBB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 298.0020699100964,
			"y": -297.0511243499449,
			"strokeColor": "#000000",
			"backgroundColor": "#12b886",
			"width": 25,
			"height": 20,
			"seed": 756603066,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "M3",
			"rawText": "M3",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "M3"
		},
		{
			"type": "rectangle",
			"version": 255,
			"versionNonce": 1729616239,
			"isDeleted": false,
			"id": "lcgFj81L9b_yZg7X113eI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.6341358314125,
			"y": -364.22322013910593,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 183.7422946962178,
			"height": 87.0358238034716,
			"seed": 924329082,
			"groupIds": [
				"Bda0wcIJR94-yfbGe5AtP"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 160,
			"versionNonce": 436205825,
			"isDeleted": false,
			"id": "KJ2pNn1GulFMiDoRiesS5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 135.3606808156025,
			"y": -30.3490385694775,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 499.7590683226313,
			"height": 1.334475341728023,
			"seed": 1031169254,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					499.7590683226313,
					1.334475341728023
				]
			]
		},
		{
			"type": "line",
			"version": 77,
			"versionNonce": 14209935,
			"isDeleted": false,
			"id": "Ov-W8hDSSr0DEk3zp2yWL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.119749138234,
			"y": -91.06742481460117,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0.6672758503641489,
			"height": 60.71841169812353,
			"seed": 639357094,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.6672758503641489,
					60.71841169812353
				]
			]
		},
		{
			"type": "line",
			"version": 23,
			"versionNonce": 880488673,
			"isDeleted": false,
			"id": "UpY_sA69k6OS_0P7Gjnkj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633.7852992495061,
			"y": -90.4001998702372,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 16.013602288735683,
			"height": 0.6672249443639657,
			"seed": 864183674,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.013602288735683,
					-0.6672249443639657
				]
			]
		},
		{
			"type": "line",
			"version": 149,
			"versionNonce": 1219856815,
			"isDeleted": false,
			"id": "U1kvvLytX72QgVf7l2k5K",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 617.1044211104063,
			"y": -269.8864588281516,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 2.0017257390920804,
			"height": 178.15178361618638,
			"seed": 1434596006,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.0017257390920804,
					178.15178361618638
				]
			]
		},
		{
			"type": "line",
			"version": 85,
			"versionNonce": 1854172353,
			"isDeleted": false,
			"id": "BH8XRmgSnnbexjLEh0JOK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 617.7716969607704,
			"y": -269.8864588281516,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 133.44702511279877,
			"height": 0,
			"seed": 1759407738,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-133.44702511279877,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 2077653967,
			"isDeleted": false,
			"id": "YR3ju-Y98WUSqcvow-iy_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 480.9884962201512,
			"y": -307.9188406228995,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0.6672758503641489,
			"height": 36.03070696165571,
			"seed": 663527014,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.6672758503641489,
					36.03070696165571
				]
			]
		},
		{
			"type": "line",
			"version": 101,
			"versionNonce": 800795809,
			"isDeleted": false,
			"id": "OiEqfU3sWm2MvM_2XOKOg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 334.19666678407214,
			"y": -308.586091020264,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 147.45900347444285,
			"height": 0,
			"seed": 897487546,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					147.45900347444285,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 60,
			"versionNonce": 508832239,
			"isDeleted": false,
			"id": "MUrcDS1yqEnfMLdhxjkZI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 335.5312184848004,
			"y": -364.6338262958392,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 1.3344498887278746,
			"height": 54.713285386847474,
			"seed": 573308966,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.3344498887278746,
					54.713285386847474
				]
			]
		},
		{
			"type": "line",
			"version": 105,
			"versionNonce": 1070526593,
			"isDeleted": false,
			"id": "LQMvQ1b0cn6zFNMrN5Wp-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.03983321560995,
			"y": -365.9683270905669,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 186.8258351579183,
			"height": 0,
			"seed": 497826150,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					186.8258351579183,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 25,
			"versionNonce": 490148879,
			"isDeleted": false,
			"id": "yuQoBiQgZD-msbyR-ZF3b",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.03983321561,
			"y": -367.9700273766587,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 14.011952908643934,
			"seed": 1100534586,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					14.011952908643934
				]
			]
		},
		{
			"type": "line",
			"version": 122,
			"versionNonce": 1149188193,
			"isDeleted": false,
			"id": "8s6ysdfy_cIKRIfVZ67iD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.7071090659741,
			"y": -354.62532486537884,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 204.17398914738231,
			"height": 0,
			"seed": 1017365542,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-204.17398914738231,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 116,
			"versionNonce": 813152815,
			"isDeleted": false,
			"id": "QBgQCYYo0iMJaSGvNfw3S",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -54.134054119771974,
			"y": -355.29254980974287,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0.6672758503641489,
			"height": 95.41461786505113,
			"seed": 1408014886,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.6672758503641489,
					95.41461786505113
				]
			]
		},
		{
			"type": "line",
			"version": 33,
			"versionNonce": 2140898369,
			"isDeleted": false,
			"id": "6TztQZUmzfvzjxVwpHpeu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -56.135779858864026,
			"y": -262.5468826281477,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 24.687679283467702,
			"height": 1.3344753417279662,
			"seed": 1526980198,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.687679283467702,
					1.3344753417279662
				]
			]
		},
		{
			"type": "line",
			"version": 113,
			"versionNonce": 2097060943,
			"isDeleted": false,
			"id": "rFpEWjXuMR7GohgfXuMz8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -31.448100575396325,
			"y": -262.5468826281477,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0.6672758503641205,
			"height": 96.08189371541522,
			"seed": 1638085434,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.6672758503641205,
					96.08189371541522
				]
			]
		},
		{
			"type": "line",
			"version": 103,
			"versionNonce": 1292063777,
			"isDeleted": false,
			"id": "zBPyWUbbOcWqKht3sKiVu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.780824725032176,
			"y": -166.4649889127325,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 84.0716665458634,
			"height": 0.6672249443639657,
			"seed": 1730216742,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-84.0716665458634,
					0.6672249443639657
				]
			]
		},
		{
			"type": "line",
			"version": 111,
			"versionNonce": 1990474351,
			"isDeleted": false,
			"id": "vIsPnuzkV6ZV3toGOVmdr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -115.73333011542977,
			"y": -165.18628030630617,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0.9263006546735539,
			"height": 122.73672722586014,
			"seed": 645221350,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.9263006546735539,
					122.73672722586014
				]
			]
		},
		{
			"type": "line",
			"version": 162,
			"versionNonce": 1621501953,
			"isDeleted": false,
			"id": "-j6NMCqyZvLgJm7KvvctM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -115.27014445198797,
			"y": -42.91273874388747,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 252.4208153700868,
			"height": 0.9263359907785116,
			"seed": 804133626,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					252.4208153700868,
					0.9263359907785116
				]
			]
		},
		{
			"type": "line",
			"version": 15,
			"versionNonce": 36770959,
			"isDeleted": false,
			"id": "-QnCpEAFBpkR_1_e5XHo9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 138.54015723621413,
			"y": -41.52325242577223,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 11.11578453660735,
			"seed": 1126818810,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					11.11578453660735
				]
			]
		},
		{
			"type": "rectangle",
			"version": 524,
			"versionNonce": 1149468641,
			"isDeleted": false,
			"id": "dZESmGIF1rddWu8KQ0FIh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -296.9595312411261,
			"y": -33.21960002239686,
			"strokeColor": "#1864ab",
			"backgroundColor": "#228be6",
			"width": 210.40002441406244,
			"height": 33.5999755859375,
			"seed": 455864087,
			"groupIds": [
				"MDefWlle_DJKiRDj_a7zV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 417,
			"versionNonce": 1465756335,
			"isDeleted": false,
			"id": "Z9yR7tsj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -285.50234304358145,
			"y": -29.591029465756236,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 191,
			"height": 25,
			"seed": 260122969,
			"groupIds": [
				"MDefWlle_DJKiRDj_a7zV"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 3: Minimization",
			"rawText": "Unit 3: Minimization",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 3: Minimization"
		},
		{
			"type": "line",
			"version": 150,
			"versionNonce": 380296129,
			"isDeleted": false,
			"id": "akRNSJCAQxZp8_bgElIFL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -36.313613505687954,
			"y": 376.5313088464262,
			"strokeColor": "#d9480f",
			"backgroundColor": "transparent",
			"width": 1.1785870576164825,
			"height": 340.6168750360205,
			"seed": 1777274618,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.1785870576164825,
					-340.6168750360205
				]
			]
		},
		{
			"type": "rectangle",
			"version": 407,
			"versionNonce": 584219855,
			"isDeleted": false,
			"id": "8L7y25qJAQjIIpSVGS4zz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -202.51382724282945,
			"y": 9.335289155613253,
			"strokeColor": "#1864ab",
			"backgroundColor": "#228be6",
			"width": 68.24794683394003,
			"height": 23.62429313993499,
			"seed": 481635863,
			"groupIds": [
				"Zby26S81Km_lGZtQQgQgk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 398,
			"versionNonce": 121355169,
			"isDeleted": false,
			"id": "6lHMvQPg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -195.52565812570435,
			"y": 10.670386448831351,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58,
			"height": 20,
			"seed": 67465,
			"groupIds": [
				"Zby26S81Km_lGZtQQgQgk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": "[[K-Maps]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "K-Maps",
			"rawText": "K-Maps",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "K-Maps"
		},
		{
			"type": "text",
			"version": 266,
			"versionNonce": 1747454703,
			"isDeleted": false,
			"id": "e4ztLcJF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -200.5220944079286,
			"y": 34.78276269761719,
			"strokeColor": "#000000",
			"backgroundColor": "#228be6",
			"width": 159,
			"height": 80,
			"seed": 1650604631,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "to create efficient \ncircuits. inputs form\nrows & columns. cell\ncontains output.",
			"rawText": "to create efficient \ncircuits. inputs form\nrows & columns. cell\ncontains output.",
			"baseline": 75,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "to create efficient \ncircuits. inputs form\nrows & columns. cell\ncontains output."
		},
		{
			"type": "text",
			"version": 43,
			"versionNonce": 375758721,
			"isDeleted": false,
			"id": "ThVTvkWG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -125.45723837158954,
			"y": 11.84622146201221,
			"strokeColor": "#000000",
			"backgroundColor": "#228be6",
			"width": 38,
			"height": 20,
			"seed": 140031479,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "used",
			"rawText": "used",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "used"
		},
		{
			"type": "text",
			"version": 467,
			"versionNonce": 602330383,
			"isDeleted": false,
			"id": "ZQFafaG6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -203.42914523163006,
			"y": 205.7319163640166,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 169,
			"height": 180,
			"seed": 1068809911,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x: dont care. can\nbe grouped with\n1s or 0s\nSOP: group all 1s \ninto rectangles    in \nsize. find consistent\nvariables. the blocks\nadd and the \ninteriors multiply:  ",
			"rawText": "x: dont care. can\nbe grouped with\n1s or 0s\nSOP: group all 1s \ninto rectangles    in \nsize. find consistent\nvariables. the blocks\nadd and the \ninteriors multiply:  ",
			"baseline": 175,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x: dont care. can\nbe grouped with\n1s or 0s\nSOP: group all 1s \ninto rectangles    in \nsize. find consistent\nvariables. the blocks\nadd and the \ninteriors multiply:  "
		},
		{
			"type": "image",
			"version": 176,
			"versionNonce": 308807521,
			"isDeleted": false,
			"id": "fYBrBD4p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -77.3847621139486,
			"y": 289.51322173354276,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18,
			"height": 13,
			"seed": 64279,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e6a4e174f9b400f3cc07024b00c6dd0baf596180",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 380,
			"versionNonce": 763845423,
			"isDeleted": false,
			"id": "P8oEhsqnyHKUo2WNBwebz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.95338120857178,
			"y": 140.60227941359935,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 118.62538542459737,
			"height": 58.81978441385599,
			"seed": 1558925369,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 76,
			"versionNonce": 1435661121,
			"isDeleted": false,
			"id": "ugHxBoN8QTwpmbCq59zSI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.9534564196444,
			"y": 141.58807094012727,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.401717602453346,
			"height": 22.344946384458666,
			"seed": 1449957465,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.401717602453346,
					-22.344946384458666
				]
			]
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 1500650831,
			"isDeleted": false,
			"id": "Db1cGmiY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -175.83988891329767,
			"y": 108.45709012468186,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 20,
			"seed": 859407511,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y z",
			"rawText": "y z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y z"
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 1145332513,
			"isDeleted": false,
			"id": "9JJChVpV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -195.22742311263633,
			"y": 122.25839712928996,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 98242809,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "line",
			"version": 105,
			"versionNonce": 1526700911,
			"isDeleted": false,
			"id": "LRvosFqrtGlEIzvxor29o",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -167.29626206862582,
			"y": 168.53345299278863,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 117.96821614393625,
			"height": 0,
			"seed": 1694754489,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					117.96821614393625,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 72,
			"versionNonce": 183326465,
			"isDeleted": false,
			"id": "HEwn9i_u5RoHnkGxTCCBK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -107.81924569821501,
			"y": 140.6022668784206,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.9858165968853712,
			"height": 59.805588475562644,
			"seed": 860963831,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.9858165968853712,
					59.805588475562644
				]
			]
		},
		{
			"type": "line",
			"version": 80,
			"versionNonce": 1719162255,
			"isDeleted": false,
			"id": "OMqbYAdfld6Ilg2CBmpRc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -137.06482051462024,
			"y": 141.25947376461795,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.328622245866768,
			"height": 57.5053706414613,
			"seed": 470619287,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.328622245866768,
					57.5053706414613
				]
			]
		},
		{
			"type": "line",
			"version": 102,
			"versionNonce": 470601441,
			"isDeleted": false,
			"id": "OY7Wd0GsyHovLgvI-gr9S",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -77.9164263900762,
			"y": 140.93086405392992,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.300205298922606,
			"height": 58.819796949034725,
			"seed": 39636407,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.300205298922606,
					58.819796949034725
				]
			]
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 320129967,
			"isDeleted": false,
			"id": "HcZBJB99",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -160.06697378527622,
			"y": 126.85882026231391,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 16,
			"seed": 1452161111,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "00",
			"rawText": "00",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "00"
		},
		{
			"type": "text",
			"version": 72,
			"versionNonce": 1848789697,
			"isDeleted": false,
			"id": "uMEr2M8K",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -128.8886330377732,
			"y": 125.9196756487512,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 16,
			"seed": 1775381751,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "01",
			"rawText": "01",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "01"
		},
		{
			"type": "text",
			"version": 85,
			"versionNonce": 2096987599,
			"isDeleted": false,
			"id": "3Ru60hEj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -96.19277534334157,
			"y": 125.34463685919931,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9,
			"height": 16,
			"seed": 1970045433,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "11",
			"rawText": "11",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "11"
		},
		{
			"type": "text",
			"version": 62,
			"versionNonce": 2046642849,
			"isDeleted": false,
			"id": "6SnNFnRF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -71.21898887891476,
			"y": 125.75537706099655,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 16,
			"seed": 1192195607,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10"
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 659221487,
			"isDeleted": false,
			"id": "4rBJnteI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -179.78313023048173,
			"y": 145.26055039994597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1080372121,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 2015186561,
			"isDeleted": false,
			"id": "aKpNj9D2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -182.0833104590468,
			"y": 177.79215964733797,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 16,
			"seed": 1753209177,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 12.582539233988287,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 503682575,
			"isDeleted": false,
			"id": "8V2HY2hi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.4523797843164,
			"y": 145.58914757545529,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1207488441,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 17,
			"versionNonce": 1599198817,
			"isDeleted": false,
			"id": "GRIBqRQ3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -156.12375753844964,
			"y": 175.4919418132366,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 215433591,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 29,
			"versionNonce": 1478884399,
			"isDeleted": false,
			"id": "ipyoKWZg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -125.85990261530841,
			"y": 145.71796258506592,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1457224759,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347338,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 577397313,
			"isDeleted": false,
			"id": "Rfn3LFrd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -127.3812027903378,
			"y": 174.30634305045257,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1289199257,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 51,
			"versionNonce": 1502912079,
			"isDeleted": false,
			"id": "XM9mbMfM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -95.0534473421084,
			"y": 173.97774587494322,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1257021721,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 49,
			"versionNonce": 776368673,
			"isDeleted": false,
			"id": "I7SufiKX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -65.80787252570315,
			"y": 174.63495276114057,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 545020151,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 355073135,
			"isDeleted": false,
			"id": "ikJw67OU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -96.36783604414558,
			"y": 143.58204333871922,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 587325495,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 668304897,
			"isDeleted": false,
			"id": "wV4Hmoo6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -67.6151444558256,
			"y": 144.81431408482595,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 531630839,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "rectangle",
			"version": 182,
			"versionNonce": 246322831,
			"isDeleted": false,
			"id": "IPZycfbYn1c3EGROMMpYd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -163.17584904562,
			"y": 141.99056540533195,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 24.708798331472394,
			"height": 53.58923565302263,
			"seed": 263137047,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 259,
			"versionNonce": 1779899873,
			"isDeleted": false,
			"id": "-gPcxEtwsD6Q-Pbx_BfP-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -166.06392093235064,
			"y": 170.22920081352885,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 114.5590096928114,
			"height": 26.955056063729785,
			"seed": 1295268279,
			"groupIds": [
				"4uPEae1RdhwrtP6iBmYNk",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 127,
			"versionNonce": 1020980399,
			"isDeleted": false,
			"id": "eRTqzbTs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -176.31232060949813,
			"y": 386.24085217194454,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 65,
			"height": 20,
			"seed": 1779186839,
			"groupIds": [
				"Dc38eT3ilFMfIDQKlsb-C",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(y z) + ",
			"rawText": "(y z) + ",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(y z) + "
		},
		{
			"type": "line",
			"version": 87,
			"versionNonce": 1142602177,
			"isDeleted": false,
			"id": "IM9vcZEVVHQA6f-TELtRP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -170.1313584541267,
			"y": 390.5257759189079,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 10.088742475217941,
			"height": 0.931266167835588,
			"seed": 1071335385,
			"groupIds": [
				"Dc38eT3ilFMfIDQKlsb-C",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.088742475217941,
					0.931266167835588
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 727154383,
			"isDeleted": false,
			"id": "hI2EzcaPdkQM8DcJxCJBv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -154.6102161845606,
			"y": 390.0601369141442,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 10.243963371267057,
			"height": 0.465639004763716,
			"seed": 1526628855,
			"groupIds": [
				"Dc38eT3ilFMfIDQKlsb-C",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.243963371267057,
					0.465639004763716
				]
			]
		},
		{
			"type": "text",
			"version": 85,
			"versionNonce": 1996478881,
			"isDeleted": false,
			"id": "B8XQFpZ5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -115.10347607404216,
			"y": 387.27196088153096,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 23,
			"height": 20,
			"seed": 1813622231,
			"groupIds": [
				"Dc38eT3ilFMfIDQKlsb-C",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(x)",
			"rawText": "(x)",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(x)"
		},
		{
			"type": "line",
			"version": 63,
			"versionNonce": 1555877103,
			"isDeleted": false,
			"id": "UBiHrRDB-8_AscJqyMfw2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -108.18814638179671,
			"y": 392.162949815896,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 10.479068943562325,
			"height": 0.6871539955999992,
			"seed": 1754042039,
			"groupIds": [
				"Dc38eT3ilFMfIDQKlsb-C",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.479068943562325,
					0.6871539955999992
				]
			]
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1945501057,
			"isDeleted": false,
			"id": "YL0Mas9e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -206.43082026738404,
			"y": 386.51941474543685,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 20,
			"seed": 1525745017,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "f =",
			"rawText": "f =",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "f ="
		},
		{
			"type": "text",
			"version": 108,
			"versionNonce": 1821595407,
			"isDeleted": false,
			"id": "zzDg1mTJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -331.34603008449983,
			"y": 11.64613707386198,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 115,
			"height": 100,
			"seed": 115948665,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "POS: same\nthing except\nas a product\nof sums. group\n0s",
			"rawText": "POS: same\nthing except\nas a product\nof sums. group\n0s",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "POS: same\nthing except\nas a product\nof sums. group\n0s"
		},
		{
			"type": "rectangle",
			"version": 451,
			"versionNonce": 1513923937,
			"isDeleted": false,
			"id": "GsJNfTG1KJRka0Sm3z34R",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.2281935604757,
			"y": 138.0525463719932,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 118.62538542459737,
			"height": 58.81978441385599,
			"seed": 1285767511,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 147,
			"versionNonce": 1901305135,
			"isDeleted": false,
			"id": "QzM8DwAlOc_6MKqIxkJ5K",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -329.2282687715484,
			"y": 139.03833789852112,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.401717602453346,
			"height": 22.344946384458666,
			"seed": 858612633,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.401717602453346,
					-22.344946384458666
				]
			]
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 891507009,
			"isDeleted": false,
			"id": "gZjUH0lm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -337.1147012652017,
			"y": 105.90735708307571,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 27,
			"height": 20,
			"seed": 1803484791,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y z",
			"rawText": "y z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y z"
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 510009167,
			"isDeleted": false,
			"id": "CBrcwQE9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -356.50223546454026,
			"y": 119.70866408768381,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 1322223737,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "line",
			"version": 176,
			"versionNonce": 2047443233,
			"isDeleted": false,
			"id": "LojtNfYT-xW3URS8y-qi8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -328.5710744205297,
			"y": 165.98371995118245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 117.96821614393625,
			"height": 0,
			"seed": 1847990167,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					117.96821614393625,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 143,
			"versionNonce": 639851887,
			"isDeleted": false,
			"id": "quXJC866jlN7jUYZNvWDh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -269.094058050119,
			"y": 138.05253383681446,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.9858165968853712,
			"height": 59.805588475562644,
			"seed": 10096985,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.9858165968853712,
					59.805588475562644
				]
			]
		},
		{
			"type": "line",
			"version": 151,
			"versionNonce": 1180611841,
			"isDeleted": false,
			"id": "3-Xit4dya9SgZeV6xrNYK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -298.3396328665242,
			"y": 138.7097407230118,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.328622245866768,
			"height": 57.5053706414613,
			"seed": 2060258487,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.328622245866768,
					57.5053706414613
				]
			]
		},
		{
			"type": "line",
			"version": 173,
			"versionNonce": 1540609935,
			"isDeleted": false,
			"id": "KLMCZIWmvs7rWVKwDKPIT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -239.1912387419801,
			"y": 138.38113101232378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.300205298922606,
			"height": 58.819796949034725,
			"seed": 769687097,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.300205298922606,
					58.819796949034725
				]
			]
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1570925793,
			"isDeleted": false,
			"id": "7IDTTAtF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -321.3417861371802,
			"y": 124.30908722070777,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19,
			"height": 16,
			"seed": 2098748887,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "00",
			"rawText": "00",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "00"
		},
		{
			"type": "text",
			"version": 143,
			"versionNonce": 363859375,
			"isDeleted": false,
			"id": "aAKqyUXC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -290.1634453896771,
			"y": 123.36994260714505,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 16,
			"seed": 1166429977,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "01",
			"rawText": "01",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "01"
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 1734617281,
			"isDeleted": false,
			"id": "FckO3VMC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -257.46758769524547,
			"y": 122.79490381759317,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 9,
			"height": 16,
			"seed": 2015136503,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "11",
			"rawText": "11",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "11"
		},
		{
			"type": "text",
			"version": 133,
			"versionNonce": 1323335631,
			"isDeleted": false,
			"id": "NR3HBpIt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -232.4938012308187,
			"y": 123.2056440193904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 16,
			"seed": 234816505,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 12.319651465437854,
			"fontFamily": 1,
			"text": "10",
			"rawText": "10",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10"
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1833134241,
			"isDeleted": false,
			"id": "zL1kOKJZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -341.05794258238564,
			"y": 142.71081735833982,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 408818711,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 121,
			"versionNonce": 159231471,
			"isDeleted": false,
			"id": "U6goYliR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -343.3581228109507,
			"y": 175.24242660573182,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 16,
			"seed": 860757209,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 12.582539233988287,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 11,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 418360449,
			"isDeleted": false,
			"id": "HXUU8zYY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -317.7271921362204,
			"y": 143.03941453384914,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 97614135,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1888491535,
			"isDeleted": false,
			"id": "0kBp31Fd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -317.39856989035354,
			"y": 172.94220877163045,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 352786873,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 841512033,
			"isDeleted": false,
			"id": "MtUonATs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.1347149672124,
			"y": 143.16822954345977,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1977301591,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 974143023,
			"isDeleted": false,
			"id": "TqpFetPC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -288.6560151422417,
			"y": 171.75661000884642,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1414363801,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 122,
			"versionNonce": 1555906625,
			"isDeleted": false,
			"id": "T2CP49Yy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -256.32825969401233,
			"y": 171.42801283333708,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 2102384503,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 120,
			"versionNonce": 1223073871,
			"isDeleted": false,
			"id": "nEnYpzob",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -227.0826848776071,
			"y": 172.08521971953442,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 567590777,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 121,
			"versionNonce": 378376225,
			"isDeleted": false,
			"id": "0mKX8ZEN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -257.6426483960495,
			"y": 141.03231029711307,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 578015383,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 135,
			"versionNonce": 250330735,
			"isDeleted": false,
			"id": "Qf1cCcEg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -228.8899568077295,
			"y": 142.2645810432198,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1272997977,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "rectangle",
			"version": 113,
			"versionNonce": 1971905537,
			"isDeleted": false,
			"id": "ZS83aA0QxQRX_0tmFgC57",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -295.74034087304443,
			"y": 141.20969452867917,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 55.56598875788097,
			"height": 22.587811936934855,
			"seed": 2100128215,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 130,
			"versionNonce": 786962575,
			"isDeleted": false,
			"id": "bJTadAn0j_dtWDQSVjt7J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -265.9244242910169,
			"y": 140.30619652702234,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 51.04842981711795,
			"height": 20.780781467381757,
			"seed": 347265753,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 632208353,
			"isDeleted": false,
			"id": "rfFF9DjB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -348.86862273735045,
			"y": 202.44425110079789,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35,
			"height": 20,
			"seed": 236502649,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347339,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "f = ",
			"rawText": "f = ",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "f = "
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1586769583,
			"isDeleted": false,
			"id": "OMcCa0hy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -319.72809805491613,
			"y": 203.05591049746397,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 59,
			"height": 20,
			"seed": 1143638679,
			"groupIds": [
				"gGZMDfd-ajVTKsa_DtyPV",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(x + z)",
			"rawText": "(x + z)",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(x + z)"
		},
		{
			"type": "line",
			"version": 94,
			"versionNonce": 655267777,
			"isDeleted": false,
			"id": "W4TWSelrtv1JgmgU1ypiR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -313.8770601072253,
			"y": 207.7696994203466,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 10.86616474394583,
			"height": 0.8358580088795691,
			"seed": 2024631639,
			"groupIds": [
				"gGZMDfd-ajVTKsa_DtyPV",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.86616474394583,
					-0.8358580088795691
				]
			]
		},
		{
			"type": "line",
			"version": 93,
			"versionNonce": 144212175,
			"isDeleted": false,
			"id": "-5PJfk0IfRCExiQ-ztaeW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -279.88542313703977,
			"y": 206.37659919604354,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 11.702033381336662,
			"height": 0.27862642196737397,
			"seed": 2085304055,
			"groupIds": [
				"gGZMDfd-ajVTKsa_DtyPV",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.702033381336662,
					0.27862642196737397
				]
			]
		},
		{
			"type": "text",
			"version": 110,
			"versionNonce": 1271396257,
			"isDeleted": false,
			"id": "aZtIoNnd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -263.446921266949,
			"y": 202.22004186007314,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 56,
			"height": 20,
			"seed": 1154452855,
			"groupIds": [
				"2bUpJ9o7TxLmjwgjGZ-4o",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "(x + y)",
			"rawText": "(x + y)",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "(x + y)"
		},
		{
			"type": "line",
			"version": 118,
			"versionNonce": 781029103,
			"isDeleted": false,
			"id": "5yfAJ2EWQA7HhWoOKK_RR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -256.76005719591234,
			"y": 205.81935698062009,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 12.816539069206101,
			"height": 0.8358686373908313,
			"seed": 495609081,
			"groupIds": [
				"2bUpJ9o7TxLmjwgjGZ-4o",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.816539069206101,
					0.8358686373908313
				]
			]
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 1980390273,
			"isDeleted": false,
			"id": "79VgwWKhe7PJlpnjxmSV8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -224.1614779359849,
			"y": 207.49109425540172,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 10.030296106555028,
			"height": 0,
			"seed": 2084535319,
			"groupIds": [
				"2bUpJ9o7TxLmjwgjGZ-4o",
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.030296106555028,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 184,
			"versionNonce": 184277263,
			"isDeleted": false,
			"id": "DEhYcrzreAtjq2JiWK60Y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -200.82603124355126,
			"y": 7.21041222125163,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 161.80976030521202,
			"height": 0.03184757447760944,
			"seed": 406293657,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-161.80976030521202,
					-0.03184757447760944
				]
			]
		},
		{
			"type": "line",
			"version": 119,
			"versionNonce": 370492257,
			"isDeleted": false,
			"id": "2vYWlq_nPXuQZiCrNMMeh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -360.74499787217957,
			"y": 7.7667257862892285,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 216.20922132946384,
			"seed": 1354986137,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					216.20922132946384
				]
			]
		},
		{
			"type": "line",
			"version": 83,
			"versionNonce": 1935400751,
			"isDeleted": false,
			"id": "VAJNXFMygkm6_T7Xj6y29",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -362.08383624533144,
			"y": 223.9759215809961,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 151.94886070122374,
			"height": 2.0081554207001773,
			"seed": 822371351,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					151.94886070122374,
					2.0081554207001773
				]
			]
		},
		{
			"type": "line",
			"version": 147,
			"versionNonce": 1748512577,
			"isDeleted": false,
			"id": "GWiDhGZtu-zm3kyxCddKv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -210.13497554410816,
			"y": 225.98405146693946,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 1.3387362341242124,
			"height": 180.73214936051932,
			"seed": 1312918391,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.3387362341242124,
					180.73214936051932
				]
			]
		},
		{
			"type": "line",
			"version": 129,
			"versionNonce": 2048270671,
			"isDeleted": false,
			"id": "IiXdSw5Q0cI0NSdNxxoX3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -210.13497554410816,
			"y": 410.0630924822832,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 168.6833189753459,
			"height": 1.3387362341242692,
			"seed": 2082591447,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					168.6833189753459,
					1.3387362341242692
				]
			]
		},
		{
			"type": "line",
			"version": 221,
			"versionNonce": 1926405921,
			"isDeleted": false,
			"id": "WGeGKqfDMkOfMRpYDudA6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -41.451656568762246,
			"y": 412.0712479029834,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 376.86003352841504,
			"seed": 1783552023,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-376.86003352841504
				]
			]
		},
		{
			"type": "line",
			"version": 78,
			"versionNonce": 1350770543,
			"isDeleted": false,
			"id": "wAdkYJKlf0G14VCkDZ8yo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -41.48526307419655,
			"y": 34.982222337336935,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 41.76849084350616,
			"height": 0.864184463473805,
			"seed": 1635040535,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-41.76849084350616,
					0.864184463473805
				]
			]
		},
		{
			"type": "line",
			"version": 59,
			"versionNonce": 1146360577,
			"isDeleted": false,
			"id": "TfeSHT1Etuu9L53q4CLbW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -84.40597056616934,
			"y": 35.558341650132164,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0.2880761392404736,
			"height": 27.07750331003745,
			"seed": 521658329,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.2880761392404736,
					-27.07750331003745
				]
			]
		},
		{
			"type": "line",
			"version": 78,
			"versionNonce": 1760254351,
			"isDeleted": false,
			"id": "V0QiGhl_K72AfYIR-Iepu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -133.95203367244434,
			"y": 9.633071471404214,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 50.410247569748805,
			"height": 0.2880596563976141,
			"seed": 1126976505,
			"groupIds": [
				"tc7R6nWBqAmavid1YliK0"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					50.410247569748805,
					-0.2880596563976141
				]
			]
		},
		{
			"type": "rectangle",
			"version": 91,
			"versionNonce": 1899760353,
			"isDeleted": false,
			"id": "D8iBTtSBGF2GMATC3rOjX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -361.8022176350675,
			"y": 232.3510811545973,
			"strokeColor": "#1864ab",
			"backgroundColor": "#228be6",
			"width": 50.05319429602895,
			"height": 17.01154226220916,
			"seed": 1648883759,
			"groupIds": [
				"AG-i9bQSOpyNjiAeOMgby",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 230,
			"versionNonce": 1485262767,
			"isDeleted": false,
			"id": "bEt0HVDh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -357.7209078401412,
			"y": 231.00602542081717,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 46,
			"height": 20,
			"seed": 38234,
			"groupIds": [
				"AG-i9bQSOpyNjiAeOMgby",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": "[[NAND]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "NAND",
			"rawText": "NAND",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NAND"
		},
		{
			"type": "image",
			"version": 172,
			"versionNonce": 1377437377,
			"isDeleted": false,
			"id": "3F5b4dc5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -343.04526389042235,
			"y": 255.59466867625784,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 104,
			"height": 16,
			"seed": 18433,
			"groupIds": [
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "75735df3a33b755658e756691d861fb3e53ef328",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 243,
			"versionNonce": 2038399439,
			"isDeleted": false,
			"id": "WuObTLJgHXMEABmOzDdnd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -363.0895933309479,
			"y": 232.81290952211015,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 1.588382339491659,
			"height": 0.39708801090461066,
			"seed": 1090833007,
			"groupIds": [
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 189,
			"versionNonce": 26052257,
			"isDeleted": false,
			"id": "B2x5UuCdqGXwlxGfH6TGh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -361.89829900236083,
			"y": 232.81290952211015,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 146.52768762254928,
			"height": 83.70622595018125,
			"seed": 426515151,
			"groupIds": [
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 639,
			"versionNonce": 1290563567,
			"isDeleted": false,
			"id": "WXUe3wNCbTtx0-Yoqyk9Y",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -265.5122417077785,
			"y": 293.99886494078845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.433499247157437,
			"height": 0,
			"seed": 1703615233,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.433499247157437,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 648,
			"versionNonce": 440797825,
			"isDeleted": false,
			"id": "dP1nJQAxNS6evKYJITjT7",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -329.74063484928786,
			"y": 286.847783814546,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.604324504969735,
			"height": 0,
			"seed": 1716654817,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					28.604324504969735,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 650,
			"versionNonce": 483826191,
			"isDeleted": false,
			"id": "enYqo3LZORgNqtpGCJpFi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -329.74063484928786,
			"y": 301.1499460670309,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.604324504969735,
			"height": 0,
			"seed": 1194266305,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					28.604324504969735,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 701,
			"versionNonce": 889393761,
			"isDeleted": false,
			"id": "xtfRn-h85sJc3jUTtUFoJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -301.1363103443181,
			"y": 279.69670268830356,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 28.604324504969735,
			"seed": 516001441,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					28.604324504969735
				]
			]
		},
		{
			"type": "line",
			"version": 764,
			"versionNonce": 1580630063,
			"isDeleted": false,
			"id": "tJUBY0FqgnFPCsyfwWFaT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -301.1363103443181,
			"y": 279.69670268830356,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.302162252484868,
			"height": 0,
			"seed": 62460545,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.302162252484868,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 706,
			"versionNonce": 647241281,
			"isDeleted": false,
			"id": "zdU2rjNxQ0vU2SuTVo7HT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -301.1363103443181,
			"y": 308.30102719327334,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14.302162252484868,
			"height": 0,
			"seed": 181738081,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					14.302162252484868,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1433,
			"versionNonce": 1391764047,
			"isDeleted": false,
			"id": "-pnyiq85Fk8raGs-PvU4c",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -286.83414809183324,
			"y": 279.69670268830356,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.664830054870054,
			"height": 28.604324504969735,
			"seed": 82126401,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.350605063981783,
					2.8170822561624242
				],
				[
					13.664830054870054,
					14.824793396950678
				],
				[
					9.573012798464688,
					26.04217769530827
				],
				[
					0,
					28.604324504969735
				]
			]
		},
		{
			"type": "ellipse",
			"version": 389,
			"versionNonce": 2111352353,
			"isDeleted": false,
			"id": "yWtvZGuJSElpB_ZUTOVcU",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -272.66332283402096,
			"y": 290.4233243776672,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.151081126242434,
			"height": 7.151081126242434,
			"seed": 2093528609,
			"groupIds": [
				"i-TTQB_mSIpH0nAlEkhL6",
				"91Mpu4HZzuchytJhxs-wi"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 178,
			"versionNonce": 1810464879,
			"isDeleted": false,
			"id": "WCKtZHVHtnIZKPgEwaoJD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -368.579984138063,
			"y": 322.7947799109051,
			"strokeColor": "#1864ab",
			"backgroundColor": "#228be6",
			"width": 42.10677122058871,
			"height": 17.225486255224496,
			"seed": 941920577,
			"groupIds": [
				"KGeX1kUqhSVCsYSUT04Yv",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 227,
			"versionNonce": 1103118849,
			"isDeleted": false,
			"id": "iehSN1oo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -364.64603919625813,
			"y": 321.2780090379527,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 35,
			"height": 20,
			"seed": 87697,
			"groupIds": [
				"KGeX1kUqhSVCsYSUT04Yv",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": "[[NOR]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "NOR",
			"rawText": "NOR",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NOR"
		},
		{
			"type": "image",
			"version": 288,
			"versionNonce": 1792907919,
			"isDeleted": false,
			"id": "ZWS7TUS6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -310.98923249249043,
			"y": 324.23517097662153,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 82,
			"height": 16,
			"seed": 58600,
			"groupIds": [
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8be8ea931a566f2775f17b6e41eb47d5801d8fbb",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 363,
			"versionNonce": 1867143649,
			"isDeleted": false,
			"id": "Ye0m4c9gddKWNXdsF6Wmk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -368.22419361884323,
			"y": 322.27596106264923,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 151.7076408866859,
			"height": 63.24473466092343,
			"seed": 832287009,
			"groupIds": [
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 721,
			"versionNonce": 1149857967,
			"isDeleted": false,
			"id": "SIjfBHrI27LiyXMePgB6A",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -266.01941123575074,
			"y": 363.2352019073474,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.03322441771234,
			"height": 0,
			"seed": 440552431,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.03322441771234,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 869,
			"versionNonce": 931558849,
			"isDeleted": false,
			"id": "YYVPWVRUI0nS0QSSkJzRK",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -324.66892111545627,
			"y": 356.7926381551301,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.315121573577958,
			"height": 0.05984215867845942,
			"seed": 2064709135,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					30.315121573577958,
					-0.05984215867845942
				]
			]
		},
		{
			"type": "line",
			"version": 776,
			"versionNonce": 1117094607,
			"isDeleted": false,
			"id": "18ot7ev5X3xj8DYRLh3JL",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -324.66892111545627,
			"y": 369.8258625728424,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 30.434793838133544,
			"height": 0.05984215867838534,
			"seed": 1019567151,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					30.434793838133544,
					-0.05984215867838534
				]
			]
		},
		{
			"type": "line",
			"version": 791,
			"versionNonce": 2106856865,
			"isDeleted": false,
			"id": "ON2klovCryjpnulFCHINP",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -298.6024722800316,
			"y": 350.27602594627393,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.51661220885617,
			"height": 26.06644883542468,
			"seed": 860356175,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.51661220885617,
					13.03322441771234
				],
				[
					0,
					26.06644883542468
				]
			]
		},
		{
			"type": "line",
			"version": 867,
			"versionNonce": 1704612079,
			"isDeleted": false,
			"id": "JzP3j5y7ysHry0DG-wf14",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -298.6024722800316,
			"y": 350.27602594627393,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.06644883542468,
			"height": 13.03322441771234,
			"seed": 561077359,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.526922226809186,
					1.3164943457211982
				],
				[
					26.06644883542468,
					13.03322441771234
				]
			]
		},
		{
			"type": "line",
			"version": 804,
			"versionNonce": 346208641,
			"isDeleted": false,
			"id": "r_n-5gN8UB39V3dJQtuCJ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -298.6024722800316,
			"y": 376.3424747816986,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.06644883542468,
			"height": 13.03322441771234,
			"seed": 1527379599,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.868675053948548,
					-1.645609645850604
				],
				[
					26.06644883542468,
					-13.03322441771234
				]
			]
		},
		{
			"type": "ellipse",
			"version": 453,
			"versionNonce": 119560975,
			"isDeleted": false,
			"id": "XIgOcJuWCMy40vRiimdAd",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -272.53602344460694,
			"y": 359.97689580291933,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.51661220885617,
			"height": 6.51661220885617,
			"seed": 650792111,
			"groupIds": [
				"jJROUxhbAwOG7aGEbCoCD",
				"0qAHvaedCl6lWPiZRgSW6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 197,
			"versionNonce": 1039262049,
			"isDeleted": false,
			"id": "ObOe68lJnagMWWU0L_UCY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -41.506818194866696,
			"y": 34.27988128786899,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0.7292071002358966,
			"height": 378.49316214170415,
			"seed": 837975105,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.7292071002358966,
					378.49316214170415
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 1000349999,
			"isDeleted": false,
			"id": "hbBaYL0XOCCZpiV6GSn5I",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -41.20883472170917,
			"y": 35.562927731341944,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 42.63578467577804,
			"height": 1.3753521238411963,
			"seed": 1328037359,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-42.63578467577804,
					-1.3753521238411963
				]
			]
		},
		{
			"type": "line",
			"version": 91,
			"versionNonce": 1724976449,
			"isDeleted": false,
			"id": "V6cMn3diBZ262rNIQaCJI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -83.84461939748721,
			"y": 36.2505906769326,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 1.0314681857261405,
			"height": 69.79885140017754,
			"seed": 915020001,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.0314681857261405,
					-69.79885140017754
				]
			]
		},
		{
			"type": "line",
			"version": 135,
			"versionNonce": 1954685775,
			"isDeleted": false,
			"id": "9x2XHIAwKlIBOSmDhTMnL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -84.18842463762235,
			"y": -34.57978137429063,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 215.24178105236285,
			"height": 0.6876629455906738,
			"seed": 1271908015,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-215.24178105236285,
					-0.6876629455906738
				]
			]
		},
		{
			"type": "line",
			"version": 93,
			"versionNonce": 648002849,
			"isDeleted": false,
			"id": "CwfuZ79j5vyR2vwWSqqWz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -299.77403716278053,
			"y": -35.955120381801905,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0.3438314727953298,
			"height": 42.97958991591351,
			"seed": 1946305537,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.3438314727953298,
					42.97958991591351
				]
			]
		},
		{
			"type": "line",
			"version": 85,
			"versionNonce": 1646190959,
			"isDeleted": false,
			"id": "EVIwUAwbSOcKrQAj5XfJP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -301.1493892866217,
			"y": 7.712145596032144,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 60.859088827869584,
			"height": 1.3753521238411963,
			"seed": 797078447,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-60.859088827869584,
					1.3753521238411963
				]
			]
		},
		{
			"type": "line",
			"version": 343,
			"versionNonce": 2093838593,
			"isDeleted": false,
			"id": "7YFCUepvfcf_an3qHfPg-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -362.35233581994635,
			"y": 8.399821657952636,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 5.845213735500238,
			"height": 377.87657290357333,
			"seed": 1502774817,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-5.845213735500238,
					377.87657290357333
				]
			]
		},
		{
			"type": "line",
			"version": 118,
			"versionNonce": 364829583,
			"isDeleted": false,
			"id": "gV3Mbpt2I5luItaOfvXvO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -367.8537443153113,
			"y": 387.30789553807676,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 155.75799188301477,
			"height": 1.3753521238412532,
			"seed": 184717633,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					155.75799188301477,
					1.3753521238412532
				]
			]
		},
		{
			"type": "line",
			"version": 76,
			"versionNonce": 1322887393,
			"isDeleted": false,
			"id": "Ls1b8NsvGuKe_9k0pfTFU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -213.47107832347797,
			"y": 388.3394293054525,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0.6876629455906595,
			"height": 23.037062818195636,
			"seed": 544081537,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.6876629455906595,
					23.037062818195636
				]
			]
		},
		{
			"type": "line",
			"version": 79,
			"versionNonce": 1671074223,
			"isDeleted": false,
			"id": "CVL-7LeUGEChPufRtefgd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -212.78341537788728,
			"y": 413.09567572028465,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 170.19917606701748,
			"height": 1.3753521238411963,
			"seed": 1436338785,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					170.19917606701748,
					1.3753521238411963
				]
			]
		},
		{
			"type": "rectangle",
			"version": 209,
			"versionNonce": 643032257,
			"isDeleted": false,
			"id": "CBCC7y0ZCd9Q8kP7GtAri",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -398.19672636020834,
			"y": -67.30362719360306,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 274.60623140190205,
			"height": 24.581148208546153,
			"seed": 964803169,
			"groupIds": [
				"eWbOyA4RWBT0c5Lbnd-Ab",
				"JAfL_69mZcMHHzeV2Ga6P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 81429455,
			"isDeleted": false,
			"id": "Z0ruvcFv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -392.92667076544365,
			"y": -67.25755935000913,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 265,
			"height": 25,
			"seed": 296282561,
			"groupIds": [
				"eWbOyA4RWBT0c5Lbnd-Ab",
				"JAfL_69mZcMHHzeV2Ga6P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 4: Combinational Logic",
			"rawText": "Unit 4: Combinational Logic",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 4: Combinational Logic"
		},
		{
			"type": "text",
			"version": 199,
			"versionNonce": 786146465,
			"isDeleted": false,
			"id": "xyT8MfnH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -344.02609296738285,
			"y": -111.52443009698635,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 219,
			"height": 40,
			"seed": 1027393423,
			"groupIds": [
				"JAfL_69mZcMHHzeV2Ga6P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347340,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a circuit whose output is a\nfunction of only its inputs",
			"rawText": "a circuit whose output is a\nfunction of only its inputs",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a circuit whose output is a\nfunction of only its inputs"
		},
		{
			"type": "rectangle",
			"version": 183,
			"versionNonce": 2039951855,
			"isDeleted": false,
			"id": "1rcQKbbo-SDG6JbKYfkQG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -347.496140860068,
			"y": -113.94746442201324,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 224.06691136795996,
			"height": 47.09371242730586,
			"seed": 2018279617,
			"groupIds": [
				"JAfL_69mZcMHHzeV2Ga6P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 1948280961,
			"isDeleted": false,
			"id": "f66DBbavEHXpyIjeeIeNe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -561.6144573610818,
			"y": -194.44165257762265,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 69.15694156170551,
			"height": 17.74825816806566,
			"seed": 486330831,
			"groupIds": [
				"NlylZlpEoun2Wz-4xS2jw",
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 321,
			"versionNonce": 718871567,
			"isDeleted": false,
			"id": "LJupfP6k",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -558.9612271746889,
			"y": -195.85503263010494,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 65,
			"height": 20,
			"seed": 85669,
			"groupIds": [
				"NlylZlpEoun2Wz-4xS2jw",
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": "[[Decoder]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Decoder",
			"rawText": "Decoder",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Decoder"
		},
		{
			"type": "text",
			"version": 229,
			"versionNonce": 1608626273,
			"isDeleted": false,
			"id": "QeaAgw2f",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -487.3712116159633,
			"y": -196.5476163129229,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 132,
			"height": 20,
			"seed": 540062465,
			"groupIds": [
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "accepts n inputs",
			"rawText": "accepts n inputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "accepts n inputs"
		},
		{
			"type": "text",
			"version": 801,
			"versionNonce": 1285079599,
			"isDeleted": false,
			"id": "Fayf9ZGk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -558.638403223473,
			"y": -173.72047237150912,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 204,
			"height": 120,
			"seed": 205181103,
			"groupIds": [
				"InQ47xfR2rTdU-sVUE4yP",
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has    outputs. it reads\nthe binary number then \noutputs a one at one of\nthe    inputs representing\nthe decimal for of the #\n",
			"rawText": "has    outputs. it reads\nthe binary number then \noutputs a one at one of\nthe    inputs representing\nthe decimal for of the #\n",
			"baseline": 115,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has    outputs. it reads\nthe binary number then \noutputs a one at one of\nthe    inputs representing\nthe decimal for of the #\n"
		},
		{
			"type": "image",
			"version": 842,
			"versionNonce": 2012150849,
			"isDeleted": false,
			"id": "VVLiCrTw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -525.0459871403272,
			"y": -108.19872157242548,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18,
			"height": 13,
			"seed": 30134,
			"groupIds": [
				"InQ47xfR2rTdU-sVUE4yP",
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "bd7b0c1c3e09ae287d0f56065c1df2be945dd5ce",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 849,
			"versionNonce": 2143200335,
			"isDeleted": false,
			"id": "V-J5BN3QpCNqI2AB2SAut",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -524.9088070804178,
			"y": -168.44943884445684,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18,
			"height": 13,
			"seed": 1586303087,
			"groupIds": [
				"InQ47xfR2rTdU-sVUE4yP",
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "8e1b854b48d80524c755e9f1196de92b09ec7c03",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 213,
			"versionNonce": 1546112033,
			"isDeleted": false,
			"id": "vOnzft_HuDsXZBk84u17l",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -562.656389336007,
			"y": -195.76588886836845,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 209.80903990369205,
			"height": 122.52208108254246,
			"seed": 224878511,
			"groupIds": [
				"iCSfArzPD5jLlRu9PiD85"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 874725999,
			"isDeleted": false,
			"id": "RicUN91rzAWe7canYuGaf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -346.7092742394667,
			"y": -219.58128301301363,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 143.0018565228549,
			"height": 20.751070367118245,
			"seed": 2136509345,
			"groupIds": [
				"NUvu6TO-zdVQVTUKQ751P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 250,
			"versionNonce": 75210753,
			"isDeleted": false,
			"id": "2PJKWwY6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -345.1624420623155,
			"y": -219.4096668946569,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 20,
			"seed": 93384,
			"groupIds": [
				"NUvu6TO-zdVQVTUKQ751P"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": "[[Tri-State Buffer]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Tri-State Buffer",
			"rawText": "Tri-State Buffer",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Tri-State Buffer"
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 1250892943,
			"isDeleted": false,
			"id": "PXZsZcue",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -197.84297393794918,
			"y": -217.60794546025673,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 134,
			"height": 20,
			"seed": 480820431,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has 2 inputs & 1",
			"rawText": "has 2 inputs & 1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has 2 inputs & 1"
		},
		{
			"type": "text",
			"version": 251,
			"versionNonce": 1055520737,
			"isDeleted": false,
			"id": "OtVkbuK5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -345.80724008923306,
			"y": -197.7591329536234,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 289,
			"height": 80,
			"seed": 1275780687,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "output. if control(c) input is active \noutput = other input. \notherwise acts as open \ncircuit",
			"rawText": "output. if control(c) input is active \noutput = other input. \notherwise acts as open \ncircuit",
			"baseline": 75,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "output. if control(c) input is active \noutput = other input. \notherwise acts as open \ncircuit"
		},
		{
			"type": "line",
			"version": 96,
			"versionNonce": 1991946927,
			"isDeleted": false,
			"id": "ZNNbyaOoLNhJLJ53LWZZ2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -347.1605150248354,
			"y": -198.8302298543759,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 0,
			"height": 79.39537048589787,
			"seed": 1543177807,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					79.39537048589787
				]
			]
		},
		{
			"type": "line",
			"version": 138,
			"versionNonce": 1837257665,
			"isDeleted": false,
			"id": "OzkaOoaKizjGwwjiWTiM-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -346.25827437283095,
			"y": -119.43485936847802,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 224.65279422180203,
			"height": 0,
			"seed": 808581551,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					224.65279422180203,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 91,
			"versionNonce": 1632535759,
			"isDeleted": false,
			"id": "3aYsKu-qttSTVllKrU-Lp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -121.1544114504693,
			"y": -119.88596248599936,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 0.902275068966162,
			"height": 52.32877043107649,
			"seed": 1335296431,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.902275068966162,
					-52.32877043107649
				]
			]
		},
		{
			"type": "line",
			"version": 76,
			"versionNonce": 73675681,
			"isDeleted": false,
			"id": "l546IBk_aiE2xGsxVN8N7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -120.25213638150313,
			"y": -171.7636297995545,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 59.99757505438191,
			"height": 0.9022062350426836,
			"seed": 1215864769,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					59.99757505438191,
					-0.9022062350426836
				]
			]
		},
		{
			"type": "line",
			"version": 61,
			"versionNonce": 165876463,
			"isDeleted": false,
			"id": "BfzpXEj3hoN16BtL0Az2Q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59.35228625815506,
			"y": -172.6658360345972,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 0.45113753448310945,
			"height": 44.20879385632628,
			"seed": 757939105,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.45113753448310945,
					-44.20879385632628
				]
			]
		},
		{
			"type": "line",
			"version": 100,
			"versionNonce": 1203705729,
			"isDeleted": false,
			"id": "_91OpJdSHEW2-muTBng_K",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59.35228625815506,
			"y": -216.42350956492126,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 147.51302536591524,
			"height": 2.7066703305706596,
			"seed": 539400207,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-147.51302536591524,
					-2.7066703305706596
				]
			]
		},
		{
			"type": "rectangle",
			"version": 258,
			"versionNonce": 1761664271,
			"isDeleted": false,
			"id": "dE5d7eNzi7lmnU6t_2yiB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -561.0608142069208,
			"y": -352.02165401585444,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 103.52941176470586,
			"height": 22.588213752297804,
			"seed": 1821170159,
			"groupIds": [
				"7ytgR5qHp4grDo1j8Z4a1",
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 311,
			"versionNonce": 1238531937,
			"isDeleted": false,
			"id": "VPj5WVbH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -555.6975787414971,
			"y": -350.9602998829567,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 95,
			"height": 20,
			"seed": 47112,
			"groupIds": [
				"7ytgR5qHp4grDo1j8Z4a1",
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": "[[Multiplexors]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Multiplexors",
			"rawText": "Multiplexors",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Multiplexors"
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 1377854255,
			"isDeleted": false,
			"id": "iGMSXmNR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -448.64163033966804,
			"y": -348.7056662128255,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 29,
			"height": 20,
			"seed": 1240897903,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has",
			"rawText": "has",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has"
		},
		{
			"type": "image",
			"version": 245,
			"versionNonce": 686680897,
			"isDeleted": false,
			"id": "LTrjGUGp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -414.6568733238725,
			"y": -345.2423203428306,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 51,
			"height": 15,
			"seed": 14219,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "cc011653266071570fc02a7a906c2a8f11f22939",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 204,
			"versionNonce": 363472207,
			"isDeleted": false,
			"id": "ofoFuz7L",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -559.0299799943595,
			"y": -324.4228595476623,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 206,
			"height": 60,
			"seed": 1197446081,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "inputs. output is one of\nthe    inputs. n is a\nbinary # to specify which ",
			"rawText": "inputs. output is one of\nthe    inputs. n is a\nbinary # to specify which ",
			"baseline": 55,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "inputs. output is one of\nthe    inputs. n is a\nbinary # to specify which "
		},
		{
			"type": "image",
			"version": 241,
			"versionNonce": 225499937,
			"isDeleted": false,
			"id": "9wuUkoAS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -524.7135854271306,
			"y": -299.2529263073003,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18,
			"height": 13,
			"seed": 14239,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "6530584ce5beeb21985de9a14aea231783a9d7a3",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "line",
			"version": 145,
			"versionNonce": 1660330863,
			"isDeleted": false,
			"id": "ONOax3CDo5C11nDguM5GG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -483.41493495338506,
			"y": -255.654910145782,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0.29328858005919756,
			"height": 45.17057010547862,
			"seed": 1041105967,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.29328858005919756,
					45.17057010547862
				]
			]
		},
		{
			"type": "line",
			"version": 44,
			"versionNonce": 1741344513,
			"isDeleted": false,
			"id": "MzPIhOu1hILl9l4e55E3A",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -482.82826828049997,
			"y": -209.89769574560998,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 17.305592696909173,
			"height": 8.212841100174131,
			"seed": 1576865249,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.305592696909173,
					-8.212841100174131
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 1783520655,
			"isDeleted": false,
			"id": "caIltK4LcA5WKocIbIAiN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -483.70822353344425,
			"y": -255.65491014578197,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 17.598926033351745,
			"height": 9.679407080524271,
			"seed": 1814380207,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.598926033351745,
					9.679407080524271
				]
			]
		},
		{
			"type": "line",
			"version": 54,
			"versionNonce": 1853572833,
			"isDeleted": false,
			"id": "0CmJDq8DcjAzBal5m-c8_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -465.5226755835908,
			"y": -245.682180917911,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0.2933333364425721,
			"height": 27.5716440721269,
			"seed": 1056035375,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.2933333364425721,
					27.5716440721269
				]
			]
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 1055511471,
			"isDeleted": false,
			"id": "RezEnEtX6S3e9N2cbuV08",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -465.5226755835908,
			"y": -232.77630854024392,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 27.864966219473615,
			"height": 0.8799552529442849,
			"seed": 2011316641,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					27.864966219473615,
					0.8799552529442849
				]
			]
		},
		{
			"type": "line",
			"version": 58,
			"versionNonce": 1544667841,
			"isDeleted": false,
			"id": "gWnvjdgrgpKtH8DJ9nbIw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -484.00155686988677,
			"y": -247.44208023470367,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 30.504809600114697,
			"height": 0.2933109582508564,
			"seed": 1966958511,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-30.504809600114697,
					-0.2933109582508564
				]
			]
		},
		{
			"type": "line",
			"version": 71,
			"versionNonce": 2029094351,
			"isDeleted": false,
			"id": "F0_A0tviiHxyNdFbWV9B5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -483.41493495338506,
			"y": -237.4693510068327,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 29.03821005247704,
			"height": 0,
			"seed": 1079402465,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-29.03821005247704,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 51,
			"versionNonce": 1831715489,
			"isDeleted": false,
			"id": "5ikiar9C31YJwE2JkfjOU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -484.00155686988677,
			"y": -226.90999986245998,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 28.744899094226128,
			"height": 0.2933221473466858,
			"seed": 739799073,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-28.744899094226128,
					0.2933221473466858
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 394130415,
			"isDeleted": false,
			"id": "Nau_Tr03nsc9Pt-PhmefS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -484.00155686988677,
			"y": -217.52390374018657,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 30.504809600114697,
			"height": 1.1732662111951129,
			"seed": 82769313,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-30.504809600114697,
					1.1732662111951129
				]
			]
		},
		{
			"type": "line",
			"version": 31,
			"versionNonce": 511624833,
			"isDeleted": false,
			"id": "al8N7KVLAo455r9-ADhhv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -477.5486262756011,
			"y": -211.65759506240266,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0,
			"height": 7.039574888979047,
			"seed": 430562817,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					7.039574888979047
				]
			]
		},
		{
			"type": "line",
			"version": 17,
			"versionNonce": 580361743,
			"isDeleted": false,
			"id": "eScBQVSiRbd6KLbMDO354",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -470.80236234487296,
			"y": -214.5907494012946,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0.29333333644251525,
			"height": 10.559362333468528,
			"seed": 1009418433,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.29333333644251525,
					10.559362333468528
				]
			]
		},
		{
			"type": "rectangle",
			"version": 253,
			"versionNonce": 717508193,
			"isDeleted": false,
			"id": "DtjHkI1BB-TxRqkGkLWYY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -563.2017156535363,
			"y": -352.3439358018396,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 208.59337144381385,
			"height": 151.64795580010752,
			"seed": 141321775,
			"groupIds": [
				"PAvMBhSo5uNvJOb--UtZH"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 534,
			"versionNonce": 221709359,
			"isDeleted": false,
			"id": "6kQz_p-qJ_qpcSyrCuYsq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -347.5010453424081,
			"y": -247.71957831706192,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 64.93548997918373,
			"height": 17.504350783775067,
			"seed": 402677761,
			"groupIds": [
				"RmuAdfY8lEeAizwfr_JFy",
				"GV5IOwDegOuJRK1icxln4",
				"wFa2EEG6g1-BqN73K9uEX"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 477,
			"versionNonce": 1221450305,
			"isDeleted": false,
			"id": "2nue55qj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -344.33508941094084,
			"y": -249.9842278080725,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62,
			"height": 20,
			"seed": 943396751,
			"groupIds": [
				"RmuAdfY8lEeAizwfr_JFy",
				"GV5IOwDegOuJRK1icxln4",
				"wFa2EEG6g1-BqN73K9uEX"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Encoder",
			"rawText": "Encoder",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Encoder"
		},
		{
			"type": "text",
			"version": 490,
			"versionNonce": 1464116815,
			"isDeleted": false,
			"id": "yv1ICBma",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -276.35439039909335,
			"y": -246.74973741714734,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 176,
			"height": 20,
			"seed": 544483119,
			"groupIds": [
				"GV5IOwDegOuJRK1icxln4",
				"wFa2EEG6g1-BqN73K9uEX"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "opposite of a decoder",
			"rawText": "opposite of a decoder",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "opposite of a decoder"
		},
		{
			"type": "rectangle",
			"version": 634,
			"versionNonce": 695921185,
			"isDeleted": false,
			"id": "CVtOAj1EKL6LlkoHBQXkT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -348.1104158665502,
			"y": -248.67802592577414,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 250.74258360578756,
			"height": 23.11811792232845,
			"seed": 1527611055,
			"groupIds": [
				"wFa2EEG6g1-BqN73K9uEX"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 187,
			"versionNonce": 1872299119,
			"isDeleted": false,
			"id": "dAbv1wPV8DkV6sIDBhu2r",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -348.40930248897547,
			"y": -368.9429865143671,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 88.08359148414877,
			"height": 18.97184530408998,
			"seed": 677128975,
			"groupIds": [
				"WYHgQdjDgF8z6AXDHJbTT",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 112,
			"versionNonce": 901447169,
			"isDeleted": false,
			"id": "nR9d9OUY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -345.69907949096915,
			"y": -370.34490722756766,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 84,
			"height": 20,
			"seed": 306729007,
			"groupIds": [
				"WYHgQdjDgF8z6AXDHJbTT",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Half-Adder",
			"rawText": "Half-Adder",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Half-Adder"
		},
		{
			"type": "text",
			"version": 116,
			"versionNonce": 1442619023,
			"isDeleted": false,
			"id": "xfuMTqLg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -253.55010181562068,
			"y": -366.95707678586956,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 156,
			"height": 40,
			"seed": 1853453345,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has 2 inputs and 2\n",
			"rawText": "has 2 inputs and 2\n",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has 2 inputs and 2\n"
		},
		{
			"type": "text",
			"version": 127,
			"versionNonce": 210605537,
			"isDeleted": false,
			"id": "eNy1XN60",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -346.3766352404707,
			"y": -344.5974010400816,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 263,
			"height": 20,
			"seed": 1856331215,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "outputs. S = sum, C = carry out",
			"rawText": "outputs. S = sum, C = carry out",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "outputs. S = sum, C = carry out"
		},
		{
			"type": "line",
			"version": 451,
			"versionNonce": 2099770543,
			"isDeleted": false,
			"id": "N-EhwFR7y54e-dxzF1xXR",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -203.7833166081402,
			"y": -304.0457716331237,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.16703897040519,
			"height": 0,
			"seed": 698934497,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.16703897040519,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 654,
			"versionNonce": 1090662849,
			"isDeleted": false,
			"id": "s10-MF_rI48-LBliDzJh2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -252.22875386255404,
			"y": -310.1014512899254,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.05401894187675,
			"height": 0.04240514818713298,
			"seed": 1541120193,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					22.05401894187675,
					0.04240514818713298
				]
			]
		},
		{
			"type": "line",
			"version": 539,
			"versionNonce": 1824753359,
			"isDeleted": false,
			"id": "ztRM6hSVQpjt7DBXPgNCb",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -252.22875386255404,
			"y": -298.00329343542376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21.887196319939118,
			"height": 0,
			"seed": 1410064545,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					21.887196319939118,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 525,
			"versionNonce": 1480085921,
			"isDeleted": false,
			"id": "XK_QIYl8g6tqnKckZGHH4",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -228.00603523534713,
			"y": -316.2259418131887,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.05567965680173,
			"height": 24.22271862720692,
			"seed": 2145985665,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.05567965680173,
					12.11135931360346
				],
				[
					0,
					24.22271862720692
				]
			]
		},
		{
			"type": "line",
			"version": 527,
			"versionNonce": 594007279,
			"isDeleted": false,
			"id": "8QS64xh5kpxEfqYbFRq8C",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -234.06171489214887,
			"y": -316.2259418131887,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.05567965680173,
			"height": 24.22271862720692,
			"seed": 1798499425,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.05567965680173,
					12.11135931360346
				],
				[
					0,
					24.22271862720692
				]
			]
		},
		{
			"type": "line",
			"version": 598,
			"versionNonce": 123696513,
			"isDeleted": false,
			"id": "23EzhGOD8f3GGROrpHtuH",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -228.00603523534713,
			"y": -316.15713094672714,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.22271862720692,
			"height": 12.11135931360346,
			"seed": 2109257793,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.570136924321547,
					1.223376161135373
				],
				[
					24.22271862720692,
					12.11135931360346
				]
			]
		},
		{
			"type": "line",
			"version": 535,
			"versionNonce": 949837583,
			"isDeleted": false,
			"id": "_W9GDnloRNw8SHHwU2msQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -228.00603523534713,
			"y": -291.9344123195202,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.22271862720692,
			"height": 12.11135931360346,
			"seed": 2035943457,
			"groupIds": [
				"cMsXP_Vf4ZfMXysF5pFHR",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					11.958448843753827,
					-1.5292125012243687
				],
				[
					24.22271862720692,
					-12.11135931360346
				]
			]
		},
		{
			"type": "line",
			"version": 512,
			"versionNonce": 834084193,
			"isDeleted": false,
			"id": "JxA26ASavVgYyB8W3gM7G",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -193.66372217661825,
			"y": -271.88582206852794,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.95097521153346,
			"height": 0,
			"seed": 1112464609,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.95097521153346,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 523,
			"versionNonce": 1054647599,
			"isDeleted": false,
			"id": "K33u_GoIXW6f745MKp9sG",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -244.19965607404086,
			"y": -278.2028138057058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.26796694871128,
			"height": 0,
			"seed": 1560451265,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					25.26796694871128,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 525,
			"versionNonce": 646891841,
			"isDeleted": false,
			"id": "kTKw8G7FawD7BYjpIY1eg",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -244.19965607404086,
			"y": -265.5688303313501,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.26796694871128,
			"height": 0,
			"seed": 93575329,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					25.26796694871128,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 576,
			"versionNonce": 1703814991,
			"isDeleted": false,
			"id": "GvHD2UJjNaMhrkPQCwwKr",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -218.93168912532954,
			"y": -284.51980554288355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 25.26796694871128,
			"seed": 766647425,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					25.26796694871128
				]
			]
		},
		{
			"type": "line",
			"version": 639,
			"versionNonce": 524679457,
			"isDeleted": false,
			"id": "AxZjWiyowwFiEJH3xAmsO",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -218.93168912532954,
			"y": -284.51980554288355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.63398347435564,
			"height": 0,
			"seed": 1696392289,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.63398347435564,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 581,
			"versionNonce": 1527407983,
			"isDeleted": false,
			"id": "weeaX28jDn1jQbOXhBkkQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -218.93168912532954,
			"y": -259.2518385941723,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.63398347435564,
			"height": 0,
			"seed": 396603457,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.63398347435564,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1308,
			"versionNonce": 2102144257,
			"isDeleted": false,
			"id": "W07aPpx_keEExyMBMxaoQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -206.2977056509739,
			"y": -284.51980554288355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12.070988571193961,
			"height": 25.26796694871128,
			"seed": 187039777,
			"groupIds": [
				"g13kUKgqSQ8WssB-btedC",
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					9.143328891070837,
					2.488502790133916
				],
				[
					12.070988571193961,
					13.095655851287137
				],
				[
					8.456433604966604,
					23.004664387833678
				],
				[
					0,
					25.26796694871128
				]
			]
		},
		{
			"type": "text",
			"version": 54,
			"versionNonce": 1855577999,
			"isDeleted": false,
			"id": "A0k6d5lE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -270.0954346797707,
			"y": -324.14734151159945,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 11,
			"height": 20,
			"seed": 1053147937,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 1210115297,
			"isDeleted": false,
			"id": "nVbnMcJd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -268.3517725309339,
			"y": -309.3262631328705,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 10,
			"height": 20,
			"seed": 1843347535,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y"
		},
		{
			"type": "line",
			"version": 118,
			"versionNonce": 1920275887,
			"isDeleted": false,
			"id": "ZuV-KJYDTfEm0qNoXkYwY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -243.28669149938432,
			"y": -309.2367940078373,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0.4359404804011433,
			"height": 31.385802277500034,
			"seed": 1559116431,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.4359404804011433,
					31.385802277500034
				]
			]
		},
		{
			"type": "line",
			"version": 86,
			"versionNonce": 1800642753,
			"isDeleted": false,
			"id": "ESTq2SRnC8MGbZpNw78wL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -250.26134009473157,
			"y": -297.68507800097876,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 0,
			"height": 32.911494186136224,
			"seed": 866043759,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					32.911494186136224
				]
			]
		},
		{
			"type": "line",
			"version": 14,
			"versionNonce": 1573160911,
			"isDeleted": false,
			"id": "a3eemTvyWdqTk9nRXqtV7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -250.26134009473157,
			"y": -264.99153742624844,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 10.026032412619656,
			"height": 0,
			"seed": 1114646113,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.026032412619656,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 14,
			"versionNonce": 881057953,
			"isDeleted": false,
			"id": "RYZ3sn54",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -180.1911714932944,
			"y": -313.7787447509306,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 11,
			"height": 20,
			"seed": 2047918625,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347341,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "S",
			"rawText": "S",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S"
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 782284271,
			"isDeleted": false,
			"id": "49xC6ums",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -170.06119608640225,
			"y": -281.5799515259458,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 12,
			"height": 20,
			"seed": 1670213089,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C",
			"rawText": "C",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C"
		},
		{
			"type": "rectangle",
			"version": 236,
			"versionNonce": 291579009,
			"isDeleted": false,
			"id": "u6EhZBpYgB3SNzMYA9Hf7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -349.5216103573082,
			"y": -369.33431353029073,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 269.5559196751406,
			"height": 115.07722692927985,
			"seed": 198622639,
			"groupIds": [
				"l-oJ14GCJIt40ivP_XLnk"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 131,
			"versionNonce": 202514447,
			"isDeleted": false,
			"id": "18kBhcTR_AsmSHtI5it-q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -575.5668902423315,
			"y": -64.07462101681423,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 86.3651584040905,
			"height": 19.845616475100513,
			"seed": 619427329,
			"groupIds": [
				"YboYHaI2hPHYwI9f4o9q9"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 56,
			"versionNonce": 229305441,
			"isDeleted": false,
			"id": "vhDmkoTp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -570.698573951915,
			"y": -64.20553584430638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 81,
			"height": 20,
			"seed": 1248734305,
			"groupIds": [
				"YboYHaI2hPHYwI9f4o9q9"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Full Adder",
			"rawText": "Full Adder",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Full Adder"
		},
		{
			"type": "text",
			"version": 52,
			"versionNonce": 672220719,
			"isDeleted": false,
			"id": "DZ2pMoBT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -483.6521231523571,
			"y": -63.88244472672602,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 71,
			"height": 20,
			"seed": 1376490017,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "3 inputs:",
			"rawText": "3 inputs:",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3 inputs:"
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 288405569,
			"isDeleted": false,
			"id": "YyOoZRnj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -571.7643724747127,
			"y": -39.3422268117735,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 266,
			"height": 40,
			"seed": 1419593921,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "z = carry out from previous term\nrest is the same as Half Adder.",
			"rawText": "z = carry out from previous term\nrest is the same as Half Adder.",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "z = carry out from previous term\nrest is the same as Half Adder."
		},
		{
			"type": "rectangle",
			"version": 223,
			"versionNonce": 1636214863,
			"isDeleted": false,
			"id": "kzWb8kJCt5ZVMGEqjsKGO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -520.7708148004667,
			"y": 5.906045798804314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 46,
			"seed": 1003281249,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "2DthqSCe"
				}
			],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 11,
			"versionNonce": 1574045729,
			"isDeleted": false,
			"id": "2DthqSCe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -509.2708148004667,
			"y": 18.906045798804314,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21,
			"height": 20,
			"seed": 1342744175,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "HA",
			"rawText": "HA",
			"baseline": 15,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kzWb8kJCt5ZVMGEqjsKGO",
			"originalText": "HA"
		},
		{
			"type": "rectangle",
			"version": 210,
			"versionNonce": 642434671,
			"isDeleted": false,
			"id": "c7smEWmH1BmGSNMBzw28w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -572.9075502282606,
			"y": 33.96803180688538,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 42,
			"height": 49,
			"seed": 477435055,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "EZVBr3dW"
				}
			],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 11,
			"versionNonce": 1300126721,
			"isDeleted": false,
			"id": "EZVBr3dW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -562.4075502282606,
			"y": 48.46803180688538,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 21,
			"height": 20,
			"seed": 1863618465,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "HA",
			"rawText": "HA",
			"baseline": 15,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "c7smEWmH1BmGSNMBzw28w",
			"originalText": "HA"
		},
		{
			"type": "line",
			"version": 725,
			"versionNonce": 354820239,
			"isDeleted": false,
			"id": "a8vdNIkEqRtJ7Ozsbr_mY",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -409.9414114198777,
			"y": 51.55939255265997,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24.60501362811226,
			"height": 0,
			"seed": 362092769,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					24.60501362811226,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 874,
			"versionNonce": 1345663969,
			"isDeleted": false,
			"id": "rMPg0vV6fb-oTnzvTZPmu",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -475.55478109484386,
			"y": 43.357721343289235,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.15397507936571,
			"height": 0.07531608360440796,
			"seed": 1679905985,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					38.15397507936571,
					-0.07531608360440796
				]
			]
		},
		{
			"type": "line",
			"version": 782,
			"versionNonce": 1607546543,
			"isDeleted": false,
			"id": "bWvP8H0xaRzp2Qfii3FM-",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -475.55478109484386,
			"y": 59.76106376203073,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.30459207717199,
			"height": 0.07531608360431472,
			"seed": 830149793,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					38.30459207717199,
					-0.07531608360431472
				]
			]
		},
		{
			"type": "line",
			"version": 796,
			"versionNonce": 705040321,
			"isDeleted": false,
			"id": "rCbZzCSYoHOQemQWQIghV",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -442.74809625736077,
			"y": 35.156050133918484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.201671209370756,
			"height": 32.806684837483026,
			"seed": 1364318337,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.201671209370756,
					16.403342418741513
				],
				[
					0,
					32.806684837483026
				]
			]
		},
		{
			"type": "line",
			"version": 872,
			"versionNonce": 1827965135,
			"isDeleted": false,
			"id": "g1QGDX_ZZ0Y6SIgSVYn1X",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -442.74809625736077,
			"y": 35.156050133918484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.806684837483026,
			"height": 16.403342418741513,
			"seed": 1969561697,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.02470010847732,
					1.6569121234384712
				],
				[
					32.806684837483026,
					16.403342418741513
				]
			]
		},
		{
			"type": "line",
			"version": 809,
			"versionNonce": 1896902561,
			"isDeleted": false,
			"id": "GB4sy4my8crzY1RkiHwXf",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 90,
			"angle": 0,
			"x": -442.74809625736077,
			"y": 67.96273497140152,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 32.806684837483026,
			"height": 16.403342418741513,
			"seed": 1803840577,
			"groupIds": [
				"ka4umL47Iei0yjntQn3ya"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.196244046758036,
					-2.0711297253338827
				],
				[
					32.806684837483026,
					-16.403342418741513
				]
			]
		},
		{
			"type": "text",
			"version": 33,
			"versionNonce": 975738607,
			"isDeleted": false,
			"id": "EBQ4ejwC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -379.02599738490846,
			"y": 41.05166317788235,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 20,
			"seed": 621577839,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C",
			"rawText": "C",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C"
		},
		{
			"type": "line",
			"version": 56,
			"versionNonce": 1266930561,
			"isDeleted": false,
			"id": "N539bioy0CEzhZRCLI461",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -475.1960082819618,
			"y": 60.1519394208581,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 53.88521494350459,
			"height": 8.980869157250737,
			"seed": 1031331937,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-53.88521494350459,
					8.980869157250737
				]
			]
		},
		{
			"type": "line",
			"version": 25,
			"versionNonce": 2113265935,
			"isDeleted": false,
			"id": "JIb0-quzOIxaxilOsrn0C",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -531.326404828034,
			"y": 41.067596030374716,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.47768544169196,
			"height": 0,
			"seed": 1421757793,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.47768544169196,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 1839184737,
			"isDeleted": false,
			"id": "W2FiHeo_nJ2g9Z33P4CLe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -475.9444021494843,
			"y": 17.492832335963982,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 86.06660803731074,
			"height": 0,
			"seed": 329377857,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					86.06660803731074,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 21,
			"versionNonce": 164947759,
			"isDeleted": false,
			"id": "4XrSqEpD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -382.76802382131325,
			"y": 6.625002833320451,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 2041952143,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "S",
			"rawText": "S",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S"
		},
		{
			"type": "text",
			"version": 24,
			"versionNonce": 1471391553,
			"isDeleted": false,
			"id": "3wsdus15",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -585.2115055739541,
			"y": 59.76179535990653,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 825940961,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 1814964559,
			"isDeleted": false,
			"id": "apXgikAw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -586.221085270027,
			"y": 34.43542553301836,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 20,
			"seed": 816406991,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y"
		},
		{
			"type": "text",
			"version": 25,
			"versionNonce": 1411323681,
			"isDeleted": false,
			"id": "G1BBzS0W",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -579.0177300589812,
			"y": 5.060509442421761,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 216490095,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "z",
			"rawText": "z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "z"
		},
		{
			"type": "line",
			"version": 88,
			"versionNonce": 1381640047,
			"isDeleted": false,
			"id": "_M2zj-CGCekQo9SmUZyS7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -566.8755988750873,
			"y": 16.370227259982244,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 45.27848562122301,
			"height": 0.37419693376128293,
			"seed": 1060946287,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					45.27848562122301,
					0.37419693376128293
				]
			]
		},
		{
			"type": "line",
			"version": 86,
			"versionNonce": 894536449,
			"isDeleted": false,
			"id": "MoI5IyXeKwgHWUsIAco3-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -577.6352890103099,
			"y": -63.448238544757714,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.701424992635566,
			"height": 71.5464463124049,
			"seed": 43746831,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.701424992635566,
					71.5464463124049
				]
			]
		},
		{
			"type": "line",
			"version": 40,
			"versionNonce": 715219343,
			"isDeleted": false,
			"id": "19DklZOkpRboJJ7Bp1KlK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -576.3590092862851,
			"y": 8.73264283665516,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 16.853507222913663,
			"height": 1.0700573093639605,
			"seed": 343796783,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.853507222913663,
					-1.0700573093639605
				]
			]
		},
		{
			"type": "line",
			"version": 69,
			"versionNonce": 1405780705,
			"isDeleted": false,
			"id": "bu9m9lXCL9mEYDRufjdzd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -593.4800282853097,
			"y": 9.26767659379719,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.337579290394956,
			"height": 78.91718833822738,
			"seed": 1351101999,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.337579290394956,
					78.91718833822738
				]
			]
		},
		{
			"type": "line",
			"version": 250,
			"versionNonce": 104617903,
			"isDeleted": false,
			"id": "GfiLfkBdi-rLXGYDQdMuF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -370.23915706040225,
			"y": 197.97578318014808,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 3.612604999867301,
			"height": 193.79089156197978,
			"seed": 615481633,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					3.612604999867301,
					-193.79089156197978
				]
			]
		},
		{
			"type": "line",
			"version": 80,
			"versionNonce": 1276739265,
			"isDeleted": false,
			"id": "IsNvAj1xVfnBv2NV7fWZX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -366.35901987458374,
			"y": 3.3823460849152838,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 59.9235358818255,
			"height": 0.80254553325301,
			"seed": 588883777,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					59.9235358818255,
					0.80254553325301
				]
			]
		},
		{
			"type": "line",
			"version": 98,
			"versionNonce": 995330511,
			"isDeleted": false,
			"id": "0MYIKdZH5vXkROPk1PnfL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -304.56288115014127,
			"y": 3.3823460849152838,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 2.1401350285681815,
			"height": 46.01272963057334,
			"seed": 848771777,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.1401350285681815,
					-46.01272963057334
				]
			]
		},
		{
			"type": "line",
			"version": 136,
			"versionNonce": 2094923425,
			"isDeleted": false,
			"id": "piC2uGOkHAwh88EBZvALO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -576.9785089658515,
			"y": -65.51081228693673,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 173.0648247187512,
			"height": 2.786367855806219,
			"seed": 158707215,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					173.0648247187512,
					2.786367855806219
				]
			]
		},
		{
			"type": "line",
			"version": 52,
			"versionNonce": 1191147503,
			"isDeleted": false,
			"id": "NAzJzovUCR35b444Y2dev",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -402.67526703955116,
			"y": -61.79565514586177,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 2.167171062228192,
			"height": 25.07738156343514,
			"seed": 289912335,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.167171062228192,
					25.07738156343514
				]
			]
		},
		{
			"type": "line",
			"version": 82,
			"versionNonce": 1153925761,
			"isDeleted": false,
			"id": "3ojNEz35ENknbY18LdG9E",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -399.5792948818577,
			"y": -37.64707467789208,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 95.04633579303271,
			"height": 0.3096043018872763,
			"seed": 1132634319,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					95.04633579303271,
					0.3096043018872763
				]
			]
		},
		{
			"type": "rectangle",
			"version": 328,
			"versionNonce": 1867031055,
			"isDeleted": false,
			"id": "5Y5SVzHvMNcB3uzs8gNDD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -460.52327510320106,
			"y": 115.26626788526355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 51,
			"seed": 1778789423,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "S0BO1r79"
				}
			],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 11,
			"versionNonce": 9800289,
			"isDeleted": false,
			"id": "S0BO1r79",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -443.02327510320106,
			"y": 130.76626788526355,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 912103183,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "FA",
			"rawText": "FA",
			"baseline": 15,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "5Y5SVzHvMNcB3uzs8gNDD",
			"originalText": "FA"
		},
		{
			"type": "text",
			"version": 79,
			"versionNonce": 623347759,
			"isDeleted": false,
			"id": "P002jook",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -453.0998522572813,
			"y": 111.30219960070289,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 823500143,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 1226282561,
			"isDeleted": false,
			"id": "mmSJcH99",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -436.4139281166174,
			"y": 110.79893615866601,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 20,
			"seed": 1566792719,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y"
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 646228559,
			"isDeleted": false,
			"id": "j25NiWr5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -420.3291331146361,
			"y": 111.02079201476928,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 589472559,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "z",
			"rawText": "z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "z"
		},
		{
			"type": "text",
			"version": 81,
			"versionNonce": 1898784289,
			"isDeleted": false,
			"id": "L2uLKjoV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -456.649613661001,
			"y": 146.35596651355863,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 20,
			"seed": 814674913,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C",
			"rawText": "C",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C"
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 1614317679,
			"isDeleted": false,
			"id": "orjWLtav",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -419.3772881871125,
			"y": 146.79966129924833,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 1284700865,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "S",
			"rawText": "S",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S"
		},
		{
			"type": "rectangle",
			"version": 385,
			"versionNonce": 1137031681,
			"isDeleted": false,
			"id": "ZO3ykPDUn4tIEC6DR2lvQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -544.829803764241,
			"y": 114.79277184488345,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 51,
			"seed": 1825954255,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "lqZ3k8tp"
				}
			],
			"updated": 1671475347342,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 68,
			"versionNonce": 574939983,
			"isDeleted": false,
			"id": "lqZ3k8tp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -527.329803764241,
			"y": 130.29277184488345,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 1466478241,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476777677,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "FA",
			"rawText": "FA",
			"baseline": 15,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ZO3ykPDUn4tIEC6DR2lvQ",
			"originalText": "FA"
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 31511009,
			"isDeleted": false,
			"id": "EIBroYQD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -537.4063809183211,
			"y": 110.8287035603228,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 867682287,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "x",
			"rawText": "x",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "x"
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 649492655,
			"isDeleted": false,
			"id": "1LtQ5xXG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -520.7204567776572,
			"y": 110.32544011828591,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10,
			"height": 20,
			"seed": 1518088833,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "y",
			"rawText": "y",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "y"
		},
		{
			"type": "text",
			"version": 179,
			"versionNonce": 546172353,
			"isDeleted": false,
			"id": "dcbWSGHl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -504.6356617756759,
			"y": 110.54729597438919,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 1081537039,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "z",
			"rawText": "z",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "z"
		},
		{
			"type": "text",
			"version": 136,
			"versionNonce": 1776388815,
			"isDeleted": false,
			"id": "tKM9KZC8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -540.9561423220408,
			"y": 145.88247047317853,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 12,
			"height": 20,
			"seed": 1546926689,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "C",
			"rawText": "C",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "C"
		},
		{
			"type": "text",
			"version": 129,
			"versionNonce": 1189907873,
			"isDeleted": false,
			"id": "RRpEXDsN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -503.68381684815233,
			"y": 146.3261652588682,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11,
			"height": 20,
			"seed": 1544280111,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "S",
			"rawText": "S",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S"
		},
		{
			"type": "line",
			"version": 25,
			"versionNonce": 1445288175,
			"isDeleted": false,
			"id": "-UQGrsbTtYU-r9TW28pE1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -452.6561743981084,
			"y": 166.72379235923358,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 15.0864351862582,
			"seed": 829090273,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					15.0864351862582
				]
			]
		},
		{
			"type": "line",
			"version": 66,
			"versionNonce": 204222849,
			"isDeleted": false,
			"id": "_KmlRAJXImIvWGO5YF6CB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -452.2124288328682,
			"y": 181.81022754549178,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.967331726597536,
			"height": 0.4437117122065217,
			"seed": 1914372527,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-19.967331726597536,
					-0.4437117122065217
				]
			]
		},
		{
			"type": "line",
			"version": 57,
			"versionNonce": 1091199759,
			"isDeleted": false,
			"id": "qx735kssOawQ-Bfn63Ewz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -472.17976055946576,
			"y": 180.92278719456186,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.7749145548934848,
			"height": 76.7632941413938,
			"seed": 1433966415,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.7749145548934848,
					-76.7632941413938
				]
			]
		},
		{
			"type": "line",
			"version": 41,
			"versionNonce": 1972132193,
			"isDeleted": false,
			"id": "177RmsoBvh-KfQxMviTqE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -473.95467511435925,
			"y": 104.15949305316806,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.29193997914342,
			"height": 0,
			"seed": 313636385,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-25.29193997914342,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 17,
			"versionNonce": 990456111,
			"isDeleted": false,
			"id": "T4vXclr_pedtXE3YPmXk9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -499.24661509350267,
			"y": 104.60320476537461,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.44367785917290803,
			"height": 10.649250358125414,
			"seed": 1498331759,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.44367785917290803,
					10.649250358125414
				]
			]
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 878478657,
			"isDeleted": false,
			"id": "1Ad9aU1j",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -464.1928143276133,
			"y": 75.8047209756406,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 48,
			"height": 20,
			"seed": 201413903,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "2-Bit:",
			"rawText": "2-Bit:",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2-Bit:"
		},
		{
			"type": "line",
			"version": 64,
			"versionNonce": 831138639,
			"isDeleted": false,
			"id": "N-zHXTwlQU-AkTaFZz7XN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -413.60893436932645,
			"y": 167.16753792447378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.8874234244131003,
			"height": 23.960804842523743,
			"seed": 263420193,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.8874234244131003,
					23.960804842523743
				]
			]
		},
		{
			"type": "line",
			"version": 62,
			"versionNonce": 603731233,
			"isDeleted": false,
			"id": "HrrORcdqFmCzI8aF-8iId",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -499.24661509350267,
			"y": 165.8363858613373,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 25.291956905660214,
			"seed": 1679429025,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					25.291956905660214
				]
			]
		},
		{
			"type": "line",
			"version": 42,
			"versionNonce": 1357244783,
			"isDeleted": false,
			"id": "S1pKSd24R_LN2QVflVRwY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -537.8501095570444,
			"y": 166.72382621226723,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.8874572774467424,
			"height": 22.62963585287045,
			"seed": 554619457,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.8874572774467424,
					22.62963585287045
				]
			]
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 131787009,
			"isDeleted": false,
			"id": "WOfIYAaj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -461.9492474243885,
			"y": 94.17739546829353,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17,
			"height": 20,
			"seed": 1607143631,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a1",
			"rawText": "a1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a1"
		},
		{
			"type": "text",
			"version": 180,
			"versionNonce": 644146063,
			"isDeleted": false,
			"id": "21DfcFuH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -551.8410922836549,
			"y": 94.45061871511489,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 24,
			"height": 20,
			"seed": 1756306977,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a2",
			"rawText": "a2",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a2"
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 158867681,
			"isDeleted": false,
			"id": "CK1tqcLy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -439.2713635630564,
			"y": 96.9096800505011,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 15,
			"height": 20,
			"seed": 1707671425,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "b1",
			"rawText": "b1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "b1"
		},
		{
			"type": "text",
			"version": 45,
			"versionNonce": 37722543,
			"isDeleted": false,
			"id": "PszQjcph",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -525.6112645224493,
			"y": 95.27031972397533,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 72138063,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "b2",
			"rawText": "b2",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "b2"
		},
		{
			"type": "line",
			"version": 37,
			"versionNonce": 1986223297,
			"isDeleted": false,
			"id": "mwLydMIGdn3IG20_g6wMx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -593.1245009282496,
			"y": 90.14654858230895,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 36.061953456222795,
			"height": 0,
			"seed": 1981444705,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					36.061953456222795,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 115,
			"versionNonce": 429820879,
			"isDeleted": false,
			"id": "KiRbq_N6L3v9tSxoD-5I6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -557.530912836483,
			"y": 89.67821894911347,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.46829390193488507,
			"height": 107.24911177412562,
			"seed": 873320943,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347342,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.46829390193488507,
					107.24911177412562
				]
			]
		},
		{
			"type": "line",
			"version": 206,
			"versionNonce": 1044126881,
			"isDeleted": false,
			"id": "ZvrOe5_xcHIHYtqGr5MrK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -557.3701129263645,
			"y": 197.31687844577743,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 186.86641787711113,
			"height": 1.4050246308470946,
			"seed": 558379489,
			"groupIds": [
				"fFVaZJhhjo2G2ukOz6o-F"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					186.86641787711113,
					1.4050246308470946
				]
			]
		},
		{
			"type": "rectangle",
			"version": 239,
			"versionNonce": 1754937839,
			"isDeleted": false,
			"id": "dzjc3QrCMVwvRwONXcQ00",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -561.3474212444705,
			"y": 201.17698942851936,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "#7950f2",
			"width": 189.36443977092796,
			"height": 25.11975788046982,
			"seed": 673980815,
			"groupIds": [
				"043hWAHw5gqTgGBsybStq",
				"fFVaZJhhjo2G2ukOz6o-F"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 248,
			"versionNonce": 816963713,
			"isDeleted": false,
			"id": "t287YUAS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -553.8041076719957,
			"y": 204.50205858131116,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 178,
			"height": 20,
			"seed": 91055,
			"groupIds": [
				"043hWAHw5gqTgGBsybStq",
				"fFVaZJhhjo2G2ukOz6o-F"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[Magnitude Comparator]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Magnitude Comparator",
			"rawText": "Magnitude Comparator",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Magnitude Comparator"
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 1413161999,
			"isDeleted": false,
			"id": "egGUG5gl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -560.0070127353206,
			"y": 228.3203951961088,
			"strokeColor": "#000000",
			"backgroundColor": "#7950f2",
			"width": 189,
			"height": 140,
			"seed": 143635617,
			"groupIds": [
				"fFVaZJhhjo2G2ukOz6o-F"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "determines larger binary\nmagnitude of 2 #s. can\nreturn the larger # or\nhave 3 ouputs. one for\nif equal. one if #1 is\nlarger. and one if #2\nis Larger",
			"rawText": "determines larger binary\nmagnitude of 2 #s. can\nreturn the larger # or\nhave 3 ouputs. one for\nif equal. one if #1 is\nlarger. and one if #2\nis Larger",
			"baseline": 135,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "determines larger binary\nmagnitude of 2 #s. can\nreturn the larger # or\nhave 3 ouputs. one for\nif equal. one if #1 is\nlarger. and one if #2\nis Larger"
		},
		{
			"type": "rectangle",
			"version": 279,
			"versionNonce": 2072258657,
			"isDeleted": false,
			"id": "n5xOLS1mQK0C8mKHkNSxG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -562.4043951047088,
			"y": 199.8590956872568,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 190.19523069017163,
			"height": 170.21673943102002,
			"seed": 263342753,
			"groupIds": [
				"fFVaZJhhjo2G2ukOz6o-F"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 129,
			"versionNonce": 209308207,
			"isDeleted": false,
			"id": "7jrc0JtlRynSQ9iVAX-tP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -371.7409412105907,
			"y": 369.9993057889672,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 4.223783767351108,
			"height": 365.05721157628045,
			"seed": 1865333167,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					4.223783767351108,
					-365.05721157628045
				]
			]
		},
		{
			"type": "line",
			"version": 88,
			"versionNonce": 1753379905,
			"isDeleted": false,
			"id": "6HBG9K9cqXVvYI5N17ikS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -366.91372030293996,
			"y": 2.5285067767568137,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 62.150250515991615,
			"height": 0,
			"seed": 816504129,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					62.150250515991615,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 52,
			"versionNonce": 775859279,
			"isDeleted": false,
			"id": "tuXNiqMBIO_KrueP4-ADK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -304.76346978694835,
			"y": 1.3217015498442777,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 40.427825485251475,
			"seed": 1559922753,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-40.427825485251475
				]
			]
		},
		{
			"type": "line",
			"version": 127,
			"versionNonce": 1535919137,
			"isDeleted": false,
			"id": "fspgLAobIidvppghPPelO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -305.9704361391272,
			"y": -42.12312549374087,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 183.43374998964123,
			"height": 0.6033911045087166,
			"seed": 213516673,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					183.43374998964123,
					-0.6033911045087166
				]
			]
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 627198575,
			"isDeleted": false,
			"id": "VW0dI0gkLyqG-od4M4O7Z",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -120.12312173145125,
			"y": -41.51971137133705,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.603437140299036,
			"height": 130.9378722352643,
			"seed": 1912389743,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.603437140299036,
					-130.9378722352643
				]
			]
		},
		{
			"type": "line",
			"version": 53,
			"versionNonce": 277944321,
			"isDeleted": false,
			"id": "K4Y0n-ob7OzA3wnxceNvS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -117.70955731341667,
			"y": -173.66438883351375,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 58.52981181735885,
			"height": 0.6034141224038763,
			"seed": 551421551,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.52981181735885,
					-0.6034141224038763
				]
			]
		},
		{
			"type": "line",
			"version": 50,
			"versionNonce": 1319969935,
			"isDeleted": false,
			"id": "wulG-IwZ6Wiis_Mnf5VSI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -56.16274393772409,
			"y": -174.26780295591763,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 3.0170015583337317,
			"height": 42.84141292118133,
			"seed": 1049445697,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-3.0170015583337317,
					-42.84141292118133
				]
			]
		},
		{
			"type": "line",
			"version": 42,
			"versionNonce": 428896225,
			"isDeleted": false,
			"id": "a-UX2Cp-hjP-TxJOnv-sz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -59.7830905647761,
			"y": -216.5058247725903,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 36.20401870000518,
			"height": 0,
			"seed": 1524038305,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-36.20401870000518,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 67,
			"versionNonce": 1507310255,
			"isDeleted": false,
			"id": "qvfhijBx1S2kC6g34yI4_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -94.17688991546487,
			"y": -214.6956054232739,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 38.014226540373954,
			"seed": 2108906625,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-38.014226540373954
				]
			]
		},
		{
			"type": "line",
			"version": 25,
			"versionNonce": 479841217,
			"isDeleted": false,
			"id": "BfXwBwEpHOtrZpr5zbQKC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -94.14415479750755,
			"y": -254.12654084964515,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 15.84168300274294,
			"height": 0.4874382595067175,
			"seed": 1403511215,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.84168300274294,
					0.4874382595067175
				]
			]
		},
		{
			"type": "line",
			"version": 111,
			"versionNonce": 1804242127,
			"isDeleted": false,
			"id": "xLXjg8Sdrm05gJxaZm07I",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -79.03363383258053,
			"y": -255.10140807154713,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 115.76614966860015,
			"seed": 1560413121,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-115.76614966860015
				]
			]
		},
		{
			"type": "line",
			"version": 104,
			"versionNonce": 1372367777,
			"isDeleted": false,
			"id": "THjdK_tdFI4rFzDqDjDoi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -77.79880824023883,
			"y": -369.5495269398948,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 272.9004465742544,
			"height": 0.9250897884977576,
			"seed": 1706981679,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-272.9004465742544,
					-0.9250897884977576
				]
			]
		},
		{
			"type": "line",
			"version": 38,
			"versionNonce": 2136873711,
			"isDeleted": false,
			"id": "Z5Uq5dDwL9Y0OuyR4Ff4Y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -352.6066783166305,
			"y": -371.34292345932204,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 17.85572488754252,
			"seed": 954416943,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					17.85572488754252
				]
			]
		},
		{
			"type": "line",
			"version": 116,
			"versionNonce": 1096322945,
			"isDeleted": false,
			"id": "5W4Nif1n0TlYWaxvXecJS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -352.9007381514376,
			"y": -353.58100655709393,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 211.37766476304307,
			"height": 1.1635438194597327,
			"seed": 1062451983,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-211.37766476304307,
					-1.1635438194597327
				]
			]
		},
		{
			"type": "line",
			"version": 130,
			"versionNonce": 165340431,
			"isDeleted": false,
			"id": "rn1k6SaMhl5fkqzW5WQe5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -563.6574242621969,
			"y": -354.9274415841721,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.235596686185545,
			"height": 289.15606931563724,
			"seed": 1967057359,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.235596686185545,
					289.15606931563724
				]
			]
		},
		{
			"type": "line",
			"version": 24,
			"versionNonce": 1098708833,
			"isDeleted": false,
			"id": "PDiaHtAEbv-Xfh-Y2BE7u",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.264724577379,
			"y": -65.3770835270437,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 13.984034467327547,
			"height": 0.20267198415351118,
			"seed": 1159761775,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-13.984034467327547,
					0.20267198415351118
				]
			]
		},
		{
			"type": "line",
			"version": 137,
			"versionNonce": 1517906735,
			"isDeleted": false,
			"id": "xd1UnGFXQLa6wVm1T8wWb",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -580.0594160567377,
			"y": -65.57974004890585,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.621314024062599,
			"height": 73.56825258910975,
			"seed": 1477898351,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.621314024062599,
					73.56825258910975
				]
			]
		},
		{
			"type": "line",
			"version": 39,
			"versionNonce": 881419073,
			"isDeleted": false,
			"id": "5o2vpsrPrtHwX1Qpkb7J0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -578.4381020326751,
			"y": 7.177840065881242,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 16.821364934019925,
			"height": 0,
			"seed": 451365377,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-16.821364934019925,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 90,
			"versionNonce": 1034038607,
			"isDeleted": false,
			"id": "WikPEdPU2at4bHSTbG48f",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -594.8541384606796,
			"y": 6.975171947300566,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.621344948645401,
			"height": 84.1069522340031,
			"seed": 1294973551,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.621344948645401,
					84.1069522340031
				]
			]
		},
		{
			"type": "line",
			"version": 73,
			"versionNonce": 115168033,
			"isDeleted": false,
			"id": "xAom4JAh-UxmAihmS0l8U",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -594.8541384606796,
			"y": 91.2847884343115,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 37.69613862652716,
			"height": 0.20266425300781066,
			"seed": 545708431,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					37.69613862652716,
					0.20266425300781066
				]
			]
		},
		{
			"type": "line",
			"version": 101,
			"versionNonce": 1588439919,
			"isDeleted": false,
			"id": "Ar7LITCB0aBJs2wSGPdZN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -557.3606795494513,
			"y": 91.0821319124494,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.215985518046864,
			"height": 107.61636508118491,
			"seed": 509069025,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.215985518046864,
					107.61636508118491
				]
			]
		},
		{
			"type": "line",
			"version": 194,
			"versionNonce": 1827161857,
			"isDeleted": false,
			"id": "O_RWMJ2Mt7Ny6a2baQoBt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -562.2246834708044,
			"y": 197.88782451931166,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.6314663033031138,
			"height": 173.30738598261217,
			"seed": 1391552879,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.6314663033031138,
					173.30738598261217
				]
			]
		},
		{
			"type": "line",
			"version": 132,
			"versionNonce": 1776575887,
			"isDeleted": false,
			"id": "PYjBsMTgDfC6L4mvlQ91h",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.812225761576,
			"y": 371.2759447860662,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 192.2266032743962,
			"height": 1.236211995279632,
			"seed": 847809889,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					192.2266032743962,
					1.236211995279632
				]
			]
		},
		{
			"type": "rectangle",
			"version": 214,
			"versionNonce": 1630125793,
			"isDeleted": false,
			"id": "mkeB36oyHALcH71x97taI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.1470627678368,
			"y": 395.17209030077646,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 267.6868037217057,
			"height": 25.88319518891643,
			"seed": 1651323233,
			"groupIds": [
				"sCoaiHfSzYr7opqQ1gseE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 1853807535,
			"isDeleted": false,
			"id": "o3drBu1p",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -561.621862293305,
			"y": 394.6229061332707,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 263,
			"height": 25,
			"seed": 1608701441,
			"groupIds": [
				"sCoaiHfSzYr7opqQ1gseE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 5: Sequential Circuits",
			"rawText": "Unit 5: Sequential Circuits",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 5: Sequential Circuits"
		},
		{
			"type": "rectangle",
			"version": 182,
			"versionNonce": 1647393473,
			"isDeleted": false,
			"id": "oLG7EzXXHUxvgx9BhZEvv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -566.5313468312268,
			"y": 427.04006555867943,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 152.60688225107003,
			"height": 19.37116121989868,
			"seed": 1325521647,
			"groupIds": [
				"Csd6MiMEZ3QmE9RpnanmG",
				"MmZnbM2YczgqdYwEDIoew"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 135,
			"versionNonce": 10849743,
			"isDeleted": false,
			"id": "wuKSs75i",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -563.141940876003,
			"y": 425.6800235659463,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 149,
			"height": 20,
			"seed": 76174,
			"groupIds": [
				"Csd6MiMEZ3QmE9RpnanmG",
				"MmZnbM2YczgqdYwEDIoew"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[Sequential Circuits]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Sequential Circuits",
			"rawText": "Sequential Circuits",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Sequential Circuits"
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1889417889,
			"isDeleted": false,
			"id": "5OX6IbMc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -407.30991820786176,
			"y": 428.0444514261634,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 114,
			"height": 20,
			"seed": 968340719,
			"groupIds": [
				"MmZnbM2YczgqdYwEDIoew"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a circuit that",
			"rawText": "a circuit that",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a circuit that"
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 460389359,
			"isDeleted": false,
			"id": "CeULE4u5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.5864270836322,
			"y": 448.3605684400344,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 272,
			"height": 40,
			"seed": 327548943,
			"groupIds": [
				"MmZnbM2YczgqdYwEDIoew"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "depends on inputs and the current\nstate of the circuit.",
			"rawText": "depends on inputs and the current\nstate of the circuit.",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "depends on inputs and the current\nstate of the circuit."
		},
		{
			"type": "rectangle",
			"version": 226,
			"versionNonce": 1293958785,
			"isDeleted": false,
			"id": "tR2D07Zw9f0UOzZ5FPMv3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -566.5313107848489,
			"y": 426.0950737183291,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 274.9758279298265,
			"height": 64.7279939856133,
			"seed": 1110346255,
			"groupIds": [
				"MmZnbM2YczgqdYwEDIoew"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 196,
			"versionNonce": 1122608655,
			"isDeleted": false,
			"id": "eZCzcSDbnNjDmI-JEbjYi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -293.59174457307887,
			"y": 400.9814870591864,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 77.57650879327133,
			"height": 19.497821675385808,
			"seed": 2086810689,
			"groupIds": [
				"H0RHPV6Ui2K_ULynN2_pW"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 207,
			"versionNonce": 1987495521,
			"isDeleted": false,
			"id": "mAHJEyJy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -290.71687985896375,
			"y": 400.42099312096354,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 74,
			"height": 20,
			"seed": 91599,
			"groupIds": [
				"H0RHPV6Ui2K_ULynN2_pW"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[Flip Flops]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Flip Flops",
			"rawText": "Flip Flops",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Flip Flops"
		},
		{
			"type": "text",
			"version": 296,
			"versionNonce": 1711803439,
			"isDeleted": false,
			"id": "PCOLKeYr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -285.2948254423586,
			"y": 418.37235522759136,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 255,
			"height": 160,
			"seed": 491847247,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "memory elements usually \ntriggered by falling or rising \nedge of a clock (stores new\nvalue when triggered). may have\nasynchronous inputs: set means\noutput = 1. reset means output\n= 0. falling edge has a bubble\nat the clock input. rising doesnt",
			"rawText": "memory elements usually \ntriggered by falling or rising \nedge of a clock (stores new\nvalue when triggered). may have\nasynchronous inputs: set means\noutput = 1. reset means output\n= 0. falling edge has a bubble\nat the clock input. rising doesnt",
			"baseline": 155,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "memory elements usually \ntriggered by falling or rising \nedge of a clock (stores new\nvalue when triggered). may have\nasynchronous inputs: set means\noutput = 1. reset means output\n= 0. falling edge has a bubble\nat the clock input. rising doesnt"
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 1735479873,
			"isDeleted": false,
			"id": "io6Zj67y4KXTI5So6KIu1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -287.78390434661026,
			"y": 421.7238798370535,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 257.20550586370314,
			"height": 160.5978259527343,
			"seed": 1355723599,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 287,
			"versionNonce": 11841103,
			"isDeleted": false,
			"id": "R1kR51G7FqlIRv81RuQjD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -568.4857959598177,
			"y": 494.42677385106344,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 90.68964158264373,
			"height": 23.658179854392017,
			"seed": 1356365633,
			"groupIds": [
				"tveaMFrmrHq-x8ZIYCxId",
				"_Yt1tZfAhADs6tD2jEX4v"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 363,
			"versionNonce": 351232545,
			"isDeleted": false,
			"id": "0FPzYdEQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.5185167797415,
			"y": 496.25430415970254,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 20,
			"seed": 48659,
			"groupIds": [
				"tveaMFrmrHq-x8ZIYCxId",
				"_Yt1tZfAhADs6tD2jEX4v"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[D Flip Flop]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "D Flip Flop",
			"rawText": "D Flip Flop",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "D Flip Flop"
		},
		{
			"type": "text",
			"version": 161,
			"versionNonce": 2110262383,
			"isDeleted": false,
			"id": "e6ALVMrc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -472.0509901094726,
			"y": 499.4348595938022,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 157,
			"height": 20,
			"seed": 995287375,
			"groupIds": [
				"_Yt1tZfAhADs6tD2jEX4v"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has 1 input: D. when",
			"rawText": "has 1 input: D. when",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has 1 input: D. when"
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 736130561,
			"isDeleted": false,
			"id": "L9nK2TA1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -565.7711517173763,
			"y": 521.1360091985365,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 271,
			"height": 40,
			"seed": 1144972111,
			"groupIds": [
				"_Yt1tZfAhADs6tD2jEX4v"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "the flip flop is triggered it stores\nvalue of D",
			"rawText": "the flip flop is triggered it stores\nvalue of D",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "the flip flop is triggered it stores\nvalue of D"
		},
		{
			"type": "rectangle",
			"version": 364,
			"versionNonce": 1493870223,
			"isDeleted": false,
			"id": "INrQARGaQ2WVU02EJTOEB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -568.1825616078227,
			"y": 494.39550832618687,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 275.37039667353366,
			"height": 69.44543324423972,
			"seed": 928488687,
			"groupIds": [
				"_Yt1tZfAhADs6tD2jEX4v"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 134,
			"versionNonce": 256118241,
			"isDeleted": false,
			"id": "KsB6NMJHaUY7JMz4jHrqv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -571.2415484175028,
			"y": 569.7196984907532,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 96.671140499898,
			"height": 21.842926330446858,
			"seed": 788768321,
			"groupIds": [
				"wx7HWvpaJ7C9Soe9BU-fj",
				"FUneVppx6L1pnkn0evblE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 127,
			"versionNonce": 20249775,
			"isDeleted": false,
			"id": "AYFOfQUB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -566.7658413400928,
			"y": 569.8742610552716,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 20,
			"seed": 70322,
			"groupIds": [
				"wx7HWvpaJ7C9Soe9BU-fj",
				"FUneVppx6L1pnkn0evblE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[T Flip Flop]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "T Flip Flop",
			"rawText": "T Flip Flop",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T Flip Flop"
		},
		{
			"type": "text",
			"version": 30,
			"versionNonce": 371829185,
			"isDeleted": false,
			"id": "MkLIC4OW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -467.6710741266602,
			"y": 571.6889454422981,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 153,
			"height": 40,
			"seed": 1904453711,
			"groupIds": [
				"FUneVppx6L1pnkn0evblE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has 1 input T. when\n",
			"rawText": "has 1 input T. when\n",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has 1 input T. when\n"
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 2045742799,
			"isDeleted": false,
			"id": "qDamWnq4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -569.3034810268886,
			"y": 594.7622642629328,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 269,
			"height": 40,
			"seed": 1473284559,
			"groupIds": [
				"FUneVppx6L1pnkn0evblE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "T=1 the current value of output\nis flipped. When T=0 output holds",
			"rawText": "T=1 the current value of output\nis flipped. When T=0 output holds",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "T=1 the current value of output\nis flipped. When T=0 output holds"
		},
		{
			"type": "rectangle",
			"version": 210,
			"versionNonce": 162580897,
			"isDeleted": false,
			"id": "pJgZGAERHhXQuWsi1O8R2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -572.5996574546486,
			"y": 569.3003952024392,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 279.0769973784096,
			"height": 65.37431949881761,
			"seed": 2143790735,
			"groupIds": [
				"FUneVppx6L1pnkn0evblE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 133,
			"versionNonce": 1037229295,
			"isDeleted": false,
			"id": "Sq_bHTQKEzHyuEi9m7P_0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -290.0657011617344,
			"y": 586.9667062773677,
			"strokeColor": "#a61e4d",
			"backgroundColor": "#e64980",
			"width": 98.63176320530133,
			"height": 19.24522208883934,
			"seed": 1479802209,
			"groupIds": [
				"A2wOfKxAqCHwMh0XIRuGG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 119,
			"versionNonce": 1661529473,
			"isDeleted": false,
			"id": "fDUAhiBg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -286.2421207195421,
			"y": 586.192669116186,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 93,
			"height": 20,
			"seed": 82248,
			"groupIds": [
				"A2wOfKxAqCHwMh0XIRuGG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": "[[JK Flip Flop]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "JK Flip Flop",
			"rawText": "JK Flip Flop",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "JK Flip Flop"
		},
		{
			"type": "text",
			"version": 23,
			"versionNonce": 1617389327,
			"isDeleted": false,
			"id": "271PFUCY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -185.17922609462113,
			"y": 587.6459293358593,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 123,
			"height": 20,
			"seed": 1181601999,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "2 inputs J & K",
			"rawText": "2 inputs J & K",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2 inputs J & K"
		},
		{
			"type": "text",
			"version": 72,
			"versionNonce": 1232180577,
			"isDeleted": false,
			"id": "LHzrFw8F",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -285.73555555762397,
			"y": 611.7024569469083,
			"strokeColor": "#000000",
			"backgroundColor": "#e64980",
			"width": 241,
			"height": 40,
			"seed": 1732755439,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Set: J=1, K=0. Reset J=0, K=1\nHold: J=K=0. Inverted: J=K=1",
			"rawText": "Set: J=1, K=0. Reset J=0, K=1\nHold: J=K=0. Inverted: J=K=1",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Set: J=1, K=0. Reset J=0, K=1\nHold: J=K=0. Inverted: J=K=1"
		},
		{
			"type": "rectangle",
			"version": 321,
			"versionNonce": 1881517359,
			"isDeleted": false,
			"id": "PxF6dep8zOTXwxB_mao5M",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -289.6852630791248,
			"y": 586.1741049673387,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 249.071990731771,
			"height": 68.26725922829905,
			"seed": 1678769761,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 204,
			"versionNonce": 1345995073,
			"isDeleted": false,
			"id": "f__DlzCB6J-XW8rHp8HfA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -564.9887550387211,
			"y": 395.67960380460124,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 350.0170138064648,
			"height": 0,
			"seed": 801383279,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					350.0170138064648,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 71,
			"versionNonce": 410398543,
			"isDeleted": false,
			"id": "QF2CwzQ3vT-okU5faevC-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -217.0649062785477,
			"y": 397.5143099500984,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 1.4675737743889385,
			"height": 22.747302530193394,
			"seed": 1420104143,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.4675737743889385,
					22.747302530193394
				]
			]
		},
		{
			"type": "line",
			"version": 119,
			"versionNonce": 1958900001,
			"isDeleted": false,
			"id": "dXtgkvVxbe2g4H6HSyiki",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -217.03336156270962,
			"y": 420.3173254534797,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 188.32639437018338,
			"height": 0.7385517836049758,
			"seed": 1932079777,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					188.32639437018338,
					0.7385517836049758
				]
			]
		},
		{
			"type": "line",
			"version": 140,
			"versionNonce": 61959535,
			"isDeleted": false,
			"id": "sam5d1qsJRhIkasYU_9cW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.686677700092986,
			"y": 421.6965988907478,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 0.7090413513243448,
			"height": 162.72748532481017,
			"seed": 555854575,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.7090413513243448,
					162.72748532481017
				]
			]
		},
		{
			"type": "line",
			"version": 11,
			"versionNonce": 1551475969,
			"isDeleted": false,
			"id": "ueNGzjp4nUwo-ThkDxvzF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -30.332184072624585,
			"y": 584.069536491702,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 10.990276186496061,
			"height": 0,
			"seed": 1149748559,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-10.990276186496061,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 83,
			"versionNonce": 2099242895,
			"isDeleted": false,
			"id": "VNV-h_otIhM-MxQqUstlA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -39.549829832615984,
			"y": 585.133125566882,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 0.7090413513243163,
			"height": 68.06901108259638,
			"seed": 2117052129,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.7090413513243163,
					68.06901108259638
				]
			]
		},
		{
			"type": "line",
			"version": 137,
			"versionNonce": 1390370017,
			"isDeleted": false,
			"id": "TMoApvyOZ7oYwjnHRsZcY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -38.67097823153102,
			"y": 653.419869261531,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 250.8107854900648,
			"height": 0.7764924247920817,
			"seed": 2017601647,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-250.8107854900648,
					0.7764924247920817
				]
			]
		},
		{
			"type": "line",
			"version": 25,
			"versionNonce": 1392123311,
			"isDeleted": false,
			"id": "VCgomION-6Gxp4R_kANUI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -290.0630104993587,
			"y": 635.0609581487793,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 0.8144862086244302,
			"height": 17.511733121340285,
			"seed": 1703651809,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.8144862086244302,
					17.511733121340285
				]
			]
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 126032065,
			"isDeleted": false,
			"id": "mKyCNjyTqz6ayf_N5dUgi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -290.87755884929754,
			"y": 635.0609581487793,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 283.4455194226573,
			"height": 3.2580069758121226,
			"seed": 1651520463,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-283.4455194226573,
					3.2580069758121226
				]
			]
		},
		{
			"type": "line",
			"version": 130,
			"versionNonce": 2020118479,
			"isDeleted": false,
			"id": "1AaYVuSvBrIWrBT6U412S",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -575.1375644805787,
			"y": 637.9117220202785,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 7.737774335218205,
			"height": 241.09161516104223,
			"seed": 1466751279,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					7.737774335218205,
					-241.09161516104223
				]
			]
		},
		{
			"type": "rectangle",
			"version": 226,
			"versionNonce": 201611425,
			"isDeleted": false,
			"id": "rBtBsCP20pb7faE50lw13",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -34.01936360667965,
			"y": 386.36430072053054,
			"strokeColor": "#495057",
			"backgroundColor": "#868e96",
			"width": 171.3936727898556,
			"height": 24.435650492475304,
			"seed": 1828922497,
			"groupIds": [
				"zWOCyEG1wCD4WkIX-BOCp"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347343,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 26,
			"versionNonce": 1736687087,
			"isDeleted": false,
			"id": "Nj00tnJm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -31.675151587225912,
			"y": 386.0194450534753,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 165,
			"height": 25,
			"seed": 878509569,
			"groupIds": [
				"zWOCyEG1wCD4WkIX-BOCp"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 6: Counters",
			"rawText": "Unit 6: Counters",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 6: Counters"
		},
		{
			"type": "rectangle",
			"version": 186,
			"versionNonce": 303209601,
			"isDeleted": false,
			"id": "oHGw9kTiHR2pTC1_tI4a3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 143.2742053492209,
			"y": 395.30661035717293,
			"strokeColor": "#495057",
			"backgroundColor": "#868e96",
			"width": 76.21993933488869,
			"height": 19.054984833722187,
			"seed": 368124865,
			"groupIds": [
				"JviCHTt6Rd9wpZ6LR4o7s"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 297,
			"versionNonce": 1129588751,
			"isDeleted": false,
			"id": "LfXWkkJG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 146.4498744977111,
			"y": 393.98345327581154,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 71,
			"height": 20,
			"seed": 67902,
			"groupIds": [
				"JviCHTt6Rd9wpZ6LR4o7s"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": "[[Counters]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Counters",
			"rawText": "Counters",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Counters"
		},
		{
			"type": "text",
			"version": 72,
			"versionNonce": 1768776801,
			"isDeleted": false,
			"id": "KmX5TqNa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -20.53132116374708,
			"y": 413.4627708304705,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 181,
			"height": 40,
			"seed": 1694325903,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a binary counter up to\nneeds n flip flops",
			"rawText": "a binary counter up to\nneeds n flip flops",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a binary counter up to\nneeds n flip flops"
		},
		{
			"type": "image",
			"version": 514,
			"versionNonce": 970083887,
			"isDeleted": false,
			"id": "4nPAcMMO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 164.54679811773872,
			"y": 416.64855231988605,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58,
			"height": 15,
			"seed": 1441,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "e04ce71266f263964899195544b56c22f62ca6c7",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 224,
			"versionNonce": 1038364737,
			"isDeleted": false,
			"id": "pIjmNibd7k9xsTSEsxOq6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23.891205114810244,
			"y": 415.2599872561488,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 250.19047509392146,
			"height": 38.31745950400858,
			"seed": 1177848289,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 155,
			"versionNonce": 635875407,
			"isDeleted": false,
			"id": "q5zxpR-XN42HsGr-SuMDl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -22.97597039664015,
			"y": 457.6785956160217,
			"strokeColor": "#495057",
			"backgroundColor": "#868e96",
			"width": 127.58657320636453,
			"height": 20.937284704194553,
			"seed": 900842767,
			"groupIds": [
				"9cQCYnkEMX0U8pQ987ini",
				"cO2rHXgTRlBRerh-5Ko2a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 157,
			"versionNonce": 357990433,
			"isDeleted": false,
			"id": "BVOFTsME",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -20.282102927010605,
			"y": 456.72756782324,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 122,
			"height": 20,
			"seed": 45076,
			"groupIds": [
				"9cQCYnkEMX0U8pQ987ini",
				"cO2rHXgTRlBRerh-5Ko2a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": "[[Ripple Counters]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Ripple Counters",
			"rawText": "Ripple Counters",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Ripple Counters"
		},
		{
			"type": "text",
			"version": 44,
			"versionNonce": 1902759535,
			"isDeleted": false,
			"id": "gnPO8Mtn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 110.49917279413319,
			"y": 459.6657929979295,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 40,
			"height": 20,
			"seed": 1750514223,
			"groupIds": [
				"cO2rHXgTRlBRerh-5Ko2a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "is an",
			"rawText": "is an",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "is an"
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 229889025,
			"isDeleted": false,
			"id": "jnuFQk8l",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -20.031660445253348,
			"y": 480.35771645957664,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 234,
			"height": 60,
			"seed": 1509646913,
			"groupIds": [
				"cO2rHXgTRlBRerh-5Ko2a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Asynchronous Counter so no\nglobal clock. each flip flop is \ntriggered by previous flip flop",
			"rawText": "Asynchronous Counter so no\nglobal clock. each flip flop is \ntriggered by previous flip flop",
			"baseline": 55,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Asynchronous Counter so no\nglobal clock. each flip flop is \ntriggered by previous flip flop"
		},
		{
			"type": "rectangle",
			"version": 244,
			"versionNonce": 925116559,
			"isDeleted": false,
			"id": "qYRHhZEb7JTpjRFY_VXiL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -22.777377112927006,
			"y": 457.70772201531406,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 249.98621250151257,
			"height": 85.58523042913941,
			"seed": 964619073,
			"groupIds": [
				"cO2rHXgTRlBRerh-5Ko2a"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 149,
			"versionNonce": 1526442977,
			"isDeleted": false,
			"id": "UynQ7w62wDsX-Yw1gqBoA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -22.05817670169708,
			"y": 548.1825201823693,
			"strokeColor": "#495057",
			"backgroundColor": "#868e96",
			"width": 166.29150595742644,
			"height": 20.48517285877142,
			"seed": 2117801135,
			"groupIds": [
				"tHYzmNCrtHAetGq9Ui8V_",
				"GBcbYqQVYeIw7QbkriV_d"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 617496239,
			"isDeleted": false,
			"id": "UC75A3hJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -17.941984148549096,
			"y": 547.8799367655917,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 161,
			"height": 20,
			"seed": 38851,
			"groupIds": [
				"tHYzmNCrtHAetGq9Ui8V_",
				"GBcbYqQVYeIw7QbkriV_d"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": "[[Synchronous Counter]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Synchronous Counter",
			"rawText": "Synchronous Counter",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Synchronous Counter"
		},
		{
			"type": "text",
			"version": 15,
			"versionNonce": 87918529,
			"isDeleted": false,
			"id": "ImflYyTg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 150.2583841525022,
			"y": 549.117583247595,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 48,
			"height": 20,
			"seed": 488257665,
			"groupIds": [
				"GBcbYqQVYeIw7QbkriV_d"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "has a",
			"rawText": "has a",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "has a"
		},
		{
			"type": "text",
			"version": 75,
			"versionNonce": 487624911,
			"isDeleted": false,
			"id": "9eBRAltk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -19.648145549483758,
			"y": 573.2178028346865,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 224,
			"height": 40,
			"seed": 1271024783,
			"groupIds": [
				"GBcbYqQVYeIw7QbkriV_d"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "global clock. so all flip flops\nare trigged by one clock",
			"rawText": "global clock. so all flip flops\nare trigged by one clock",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "global clock. so all flip flops\nare trigged by one clock"
		},
		{
			"type": "rectangle",
			"version": 224,
			"versionNonce": 1721296801,
			"isDeleted": false,
			"id": "Y6v9Q6K-48SOphK-IQP6e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23.263169294043294,
			"y": 547.5800009024357,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 250.03982418359408,
			"height": 67.48064242436851,
			"seed": 150224801,
			"groupIds": [
				"GBcbYqQVYeIw7QbkriV_d"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 95,
			"versionNonce": 1765624705,
			"isDeleted": false,
			"id": "X9kleA3LTsVZpqeorioYu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 228.58409781054922,
			"y": 617.4706744790176,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 3.614977777038689,
			"height": 231.36212872146177,
			"seed": 391509295,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-3.614977777038689,
					-231.36212872146177
				]
			]
		},
		{
			"type": "line",
			"version": 127,
			"versionNonce": 1286596879,
			"isDeleted": false,
			"id": "mHYNJBwu8qTb2oxuEfNot",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -33.50574423154879,
			"y": 387.3135728255427,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 259.07731459371155,
			"height": 1.2050270679868618,
			"seed": 2145927041,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					259.07731459371155,
					-1.2050270679868618
				]
			]
		},
		{
			"type": "line",
			"version": 29,
			"versionNonce": 90846049,
			"isDeleted": false,
			"id": "3b_mbv239aNGbCfb599lU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -34.71078279141589,
			"y": 387.9160691217158,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 0.6024962961731077,
			"height": 23.49772329091826,
			"seed": 941483215,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.6024962961731077,
					23.49772329091826
				]
			]
		},
		{
			"type": "line",
			"version": 5,
			"versionNonce": 68022063,
			"isDeleted": false,
			"id": "fyIbMhwB6SyrFgg9mGvws",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -33.50574423154879,
			"y": 412.6187850049803,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 10.242574937505488,
			"height": 0,
			"seed": 2135793153,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.242574937505488,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 130,
			"versionNonce": 2137988929,
			"isDeleted": false,
			"id": "eXzHslcqzBXIyC5ABrfw4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -23.2631692940433,
			"y": 413.82380058108697,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 0.6024962961731077,
			"height": 204.24937019410368,
			"seed": 1067668655,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.6024962961731077,
					204.24937019410368
				]
			]
		},
		{
			"type": "rectangle",
			"version": 222,
			"versionNonce": 1241919823,
			"isDeleted": false,
			"id": "ouVIAsz19oVUxo8S4A8_x",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 287.18818132970137,
			"y": 343.9854889295719,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 301.64134282172614,
			"height": 27.622834363694665,
			"seed": 608812865,
			"groupIds": [
				"-FUEZkidxDL_BSsUUzzWx"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 1705742113,
			"isDeleted": false,
			"id": "n5TSPO5p",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 291.2995221220568,
			"y": 346.04767542344484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 292,
			"height": 25,
			"seed": 1855211969,
			"groupIds": [
				"-FUEZkidxDL_BSsUUzzWx"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475347344,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Unit 7: Finite State Machines",
			"rawText": "Unit 7: Finite State Machines",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Unit 7: Finite State Machines"
		},
		{
			"type": "rectangle",
			"version": 270,
			"versionNonce": 248409505,
			"isDeleted": false,
			"id": "WPW_-ZRo63oF-DG9GcX2s",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.95806908658747,
			"y": 385.904495352853,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 182.06872349341094,
			"height": 25.169070339618084,
			"seed": 1754811745,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475383820,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 141,
			"versionNonce": 1744021199,
			"isDeleted": false,
			"id": "68DlqW6w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 237.3278690306591,
			"y": 388.772692207863,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 174,
			"height": 20,
			"seed": 91261,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475376795,
			"link": "[[Finite State Machines]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Finite State Machines",
			"rawText": "Finite State Machines",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Finite State Machines"
		},
		{
			"type": "text",
			"version": 19,
			"versionNonce": 1821247585,
			"isDeleted": false,
			"id": "Io1DWP4s",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 422.06819638279705,
			"y": 392.0065807334664,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 154,
			"height": 20,
			"seed": 1020400001,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475402799,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "a system that has",
			"rawText": "a system that has",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "a system that has"
		},
		{
			"type": "text",
			"version": 40,
			"versionNonce": 921246895,
			"isDeleted": false,
			"id": "uk6vIJTa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.32302899475087,
			"y": 414.8117845674303,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 271,
			"height": 20,
			"seed": 1565545537,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475416737,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "finite states, inputs, and outputs",
			"rawText": "finite states, inputs, and outputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "finite states, inputs, and outputs"
		},
		{
			"type": "rectangle",
			"version": 149,
			"versionNonce": 1954503823,
			"isDeleted": false,
			"id": "GLYhsITtOD9-BttEAos5q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.7319517947407,
			"y": 386.2477389426285,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 345.26027260363946,
			"height": 48.79254183656104,
			"seed": 1987730255,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475439314,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 150,
			"versionNonce": 167583617,
			"isDeleted": false,
			"id": "GyDjiV2SkuAiNQ4q2EK4t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 513.1089555426598,
			"y": 215.62855578691625,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 145.03159922405877,
			"height": 19.36623903885271,
			"seed": 1000959855,
			"groupIds": [
				"nh-mWBKbX8P0ico0_erPD",
				"Zo-c_ZuliXH1vhn4ImXlJ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475546374,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 473,
			"versionNonce": 2005357839,
			"isDeleted": false,
			"id": "6mmrx45V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 515.9385495032659,
			"y": 214.66786570690715,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 141,
			"height": 20,
			"seed": 3822,
			"groupIds": [
				"nh-mWBKbX8P0ico0_erPD",
				"Zo-c_ZuliXH1vhn4ImXlJ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475546374,
			"link": "[[Deterministic FSM]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Deterministic FSM",
			"rawText": "Deterministic FSM",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Deterministic FSM"
		},
		{
			"type": "text",
			"version": 97,
			"versionNonce": 655329121,
			"isDeleted": false,
			"id": "AGXZpEnY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 515.6911141810544,
			"y": 235.67164145866155,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 131,
			"height": 100,
			"seed": 1428941505,
			"groupIds": [
				"Zo-c_ZuliXH1vhn4ImXlJ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475546374,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "an FSM if every\ncombination of\nstate and input\nresults in only 1\nstate transition",
			"rawText": "an FSM if every\ncombination of\nstate and input\nresults in only 1\nstate transition",
			"baseline": 95,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "an FSM if every\ncombination of\nstate and input\nresults in only 1\nstate transition"
		},
		{
			"type": "rectangle",
			"version": 157,
			"versionNonce": 957864751,
			"isDeleted": false,
			"id": "7_RIIX92zVtUz1EOrvmoA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 512.6786012419154,
			"y": 214.76783076846328,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 147.1834363956376,
			"height": 120.0706721907082,
			"seed": 1335122305,
			"groupIds": [
				"Zo-c_ZuliXH1vhn4ImXlJ"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671475546374,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 144,
			"versionNonce": 1754979393,
			"isDeleted": false,
			"id": "iwg0ZNvkYoBoN1_Ke1O1V",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.3288709252942,
			"y": 440.53080670084904,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 90.1424658039432,
			"height": 17.438275426616883,
			"seed": 168101839,
			"groupIds": [
				"Sci_TWuNSwzgsk7mU9Nv5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 675333199,
			"isDeleted": false,
			"id": "RowuFtCe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.14288805864106,
			"y": 438.78432494623723,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 20,
			"seed": 96556,
			"groupIds": [
				"Sci_TWuNSwzgsk7mU9Nv5"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": "[[Moore FSM]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Moore FSM",
			"rawText": "Moore FSM",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Moore FSM"
		},
		{
			"type": "text",
			"version": 32,
			"versionNonce": 207072289,
			"isDeleted": false,
			"id": "taSd52Ge",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 327.3941531268884,
			"y": 441.2032043480929,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 240,
			"height": 20,
			"seed": 1307269665,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "an FSM where the output only",
			"rawText": "an FSM where the output only",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "an FSM where the output only"
		},
		{
			"type": "text",
			"version": 34,
			"versionNonce": 1197564527,
			"isDeleted": false,
			"id": "TyFJRklW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.02754105617825,
			"y": 460.9353144983485,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 238,
			"height": 20,
			"seed": 1443313743,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "depends on the current state",
			"rawText": "depends on the current state",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "depends on the current state"
		},
		{
			"type": "text",
			"version": 496,
			"versionNonce": 1672445953,
			"isDeleted": false,
			"id": "tWWV7awf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 235.800035605662,
			"y": 484.6880918883827,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47,
			"height": 20,
			"seed": 2021922575,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "start",
			"rawText": "start",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "start"
		},
		{
			"type": "ellipse",
			"version": 326,
			"versionNonce": 285817999,
			"isDeleted": false,
			"id": "6Hzea2nEc52GF175QO0Na",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 371.30313953527553,
			"y": 501.02924276969725,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 1243727201,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "6aY757-UnODXPbnd8d-Dm",
					"type": "arrow"
				},
				{
					"id": "8pdXFXgVebKVKrEbyRAbI",
					"type": "arrow"
				},
				{
					"id": "zZzTOV1geFbvaCoPy02Hd",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 276,
			"versionNonce": 1285674977,
			"isDeleted": false,
			"id": "6aY757-UnODXPbnd8d-Dm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 318.2630148386635,
			"y": 505.25133733371604,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 55.92467171874762,
			"height": 7.46624011713061,
			"seed": 1350651887,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "yllsjBEfEzGwUudLYWxen",
				"focus": -0.5798182186204229,
				"gap": 5.869549375654508
			},
			"endBinding": {
				"elementId": "Yj4wlmam",
				"focus": 1.7615771045050173,
				"gap": 15.367430174154379
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					25.155286368868815,
					-6.0023030947830875
				],
				[
					55.92467171874762,
					1.4639370223475225
				]
			]
		},
		{
			"type": "arrow",
			"version": 306,
			"versionNonce": 686871215,
			"isDeleted": false,
			"id": "8pdXFXgVebKVKrEbyRAbI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 363.81875520357164,
			"y": 532.1298745325378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 37.77984709694772,
			"height": 5.055688646686349,
			"seed": 476730337,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "6Hzea2nEc52GF175QO0Na",
				"focus": -0.14097625825753626,
				"gap": 9.771440158560388
			},
			"endBinding": {
				"elementId": "yllsjBEfEzGwUudLYWxen",
				"focus": 0.12454727349353259,
				"gap": 8.414021959713544
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-15.749140445128887,
					4.355230887630228
				],
				[
					-37.77984709694772,
					-0.7004577590561212
				]
			]
		},
		{
			"type": "text",
			"version": 80,
			"versionNonce": 960377793,
			"isDeleted": false,
			"id": "6ksUCndo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 382.59966608767314,
			"y": 504.7557212245732,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 1193425935,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s2",
			"rawText": "s2",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s2"
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 666936527,
			"isDeleted": false,
			"id": "Yj4wlmam",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 389.5551167315655,
			"y": 520.4053303994303,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 878315311,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "6aY757-UnODXPbnd8d-Dm",
					"type": "arrow"
				},
				{
					"id": "ZSvq7Sfp14BEzubDD6T2r",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "ellipse",
			"version": 374,
			"versionNonce": 765727649,
			"isDeleted": false,
			"id": "yllsjBEfEzGwUudLYWxen",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 275.2514117514618,
			"y": 502.25407097238224,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 377323759,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "6aY757-UnODXPbnd8d-Dm",
					"type": "arrow"
				},
				{
					"id": "8pdXFXgVebKVKrEbyRAbI",
					"type": "arrow"
				},
				{
					"id": "UGOgXOBxZCpEABYniJpvJ",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 130,
			"versionNonce": 2098279151,
			"isDeleted": false,
			"id": "QBxzeCee",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 286.5479383038594,
			"y": 505.9805494272581,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 15,
			"height": 20,
			"seed": 337480463,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "8pdXFXgVebKVKrEbyRAbI",
					"type": "arrow"
				},
				{
					"id": "6aY757-UnODXPbnd8d-Dm",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s1",
			"rawText": "s1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s1"
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 2114123649,
			"isDeleted": false,
			"id": "1OwPlQId",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 293.50338894775166,
			"y": 521.6301586021153,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1855959393,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "YtH_3tdNZGrnsM5omL57W",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "ellipse",
			"version": 342,
			"versionNonce": 292224271,
			"isDeleted": false,
			"id": "XczNDZLwi96OTNAV1aYyS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 326.3908209332321,
			"y": 556.7876303934868,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 1896184175,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "YtH_3tdNZGrnsM5omL57W",
					"type": "arrow"
				},
				{
					"id": "ZSvq7Sfp14BEzubDD6T2r",
					"type": "arrow"
				},
				{
					"id": "zZzTOV1geFbvaCoPy02Hd",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 98,
			"versionNonce": 1285185377,
			"isDeleted": false,
			"id": "Cbjpsg78",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 337.6873474856297,
			"y": 560.5141088483626,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 1007842191,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "ZSvq7Sfp14BEzubDD6T2r",
					"type": "arrow"
				},
				{
					"id": "UGOgXOBxZCpEABYniJpvJ",
					"type": "arrow"
				}
			],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s3",
			"rawText": "s3",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s3"
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 675709743,
			"isDeleted": false,
			"id": "MPhBDEdl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 344.6427981295221,
			"y": 576.1637180232199,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 455839969,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 6,
			"versionNonce": 1203358529,
			"isDeleted": false,
			"id": "xgJ2sF1i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 347.052448364012,
			"y": 534.2654632505771,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1763480481,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "text",
			"version": 6,
			"versionNonce": 34358607,
			"isDeleted": false,
			"id": "gCc0C1NA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 339.0218725690953,
			"y": 482.51295823322397,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1571202159,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "arrow",
			"version": 82,
			"versionNonce": 666942241,
			"isDeleted": false,
			"id": "YtH_3tdNZGrnsM5omL57W",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 289.053943732608,
			"y": 551.5806152263597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.106913168329697,
			"height": 24.537828882517147,
			"seed": 1011717295,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "1OwPlQId",
				"focus": 1.8343565617958972,
				"gap": 9.950456624244339
			},
			"endBinding": {
				"elementId": "XczNDZLwi96OTNAV1aYyS",
				"focus": -0.667062558052497,
				"gap": 9.238130883810786
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					8.92284686636981,
					14.722710944694086
				],
				[
					28.106913168329697,
					24.537828882517147
				]
			]
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 1041548143,
			"isDeleted": false,
			"id": "fS87AeXi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 297.53062102529174,
			"y": 547.2035980144053,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1723744385,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "arrow",
			"version": 149,
			"versionNonce": 1830727425,
			"isDeleted": false,
			"id": "ZSvq7Sfp14BEzubDD6T2r",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 399.6971904148588,
			"y": 548.011462864628,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.199388237377775,
			"height": 23.199388237377775,
			"seed": 467718113,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Yj4wlmam",
				"focus": -1.813208210319557,
				"gap": 7.606132465197675
			},
			"endBinding": {
				"elementId": "XczNDZLwi96OTNAV1aYyS",
				"focus": 0.4599460544988631,
				"gap": 6.737968523357328
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-8.030507718997626,
					14.276541371007966
				],
				[
					-23.199388237377775,
					23.199388237377775
				]
			]
		},
		{
			"type": "text",
			"version": 42,
			"versionNonce": 2091416975,
			"isDeleted": false,
			"id": "zZppSuQO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 378.2824123963065,
			"y": 544.0805811884002,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1566679457,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "arrow",
			"version": 98,
			"versionNonce": 1582507745,
			"isDeleted": false,
			"id": "zZzTOV1geFbvaCoPy02Hd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 379.62078496552664,
			"y": 588.6104092990188,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.58372661285165,
			"height": 47.73721711989481,
			"seed": 1170396303,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "XczNDZLwi96OTNAV1aYyS",
				"focus": 1.3259485450297224,
				"gap": 11.66036570093934
			},
			"endBinding": {
				"elementId": "6Hzea2nEc52GF175QO0Na",
				"focus": -1.301803184879182,
				"gap": 9.202159541134634
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					25.43016802988933,
					-17.399558197012993
				],
				[
					36.58372661285165,
					-47.73721711989481
				]
			]
		},
		{
			"type": "text",
			"version": 7,
			"versionNonce": 1090515887,
			"isDeleted": false,
			"id": "zbAwhBGz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 410.85074899782114,
			"y": 568.6184441088768,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 171393743,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "arrow",
			"version": 87,
			"versionNonce": 1173201601,
			"isDeleted": false,
			"id": "UGOgXOBxZCpEABYniJpvJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 324.74533119808734,
			"y": 590.8411210156114,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 50.41413244813299,
			"height": 45.506505403302526,
			"seed": 559029007,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "Cbjpsg78",
				"focus": -2.080474256854934,
				"gap": 12.942016287542344
			},
			"endBinding": {
				"elementId": "yllsjBEfEzGwUudLYWxen",
				"focus": 1.4597076529890947,
				"gap": 11.572214838227552
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-32.56840467743376,
					-14.722676906734591
				],
				[
					-50.41413244813299,
					-45.506505403302526
				]
			]
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 323200463,
			"isDeleted": false,
			"id": "5PyjadcF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 281.0233338997317,
			"y": 573.9721726514745,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 103478959,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 1888330401,
			"isDeleted": false,
			"id": "JGJsVhmQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 443.35953625024,
			"y": 489.7197477961221,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 47,
			"height": 20,
			"seed": 1132677839,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "inputs",
			"rawText": "inputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "inputs"
		},
		{
			"type": "text",
			"version": 11,
			"versionNonce": 1653347311,
			"isDeleted": false,
			"id": "caf1lNKf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 443.7543833124987,
			"y": 512.2280940579572,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 63,
			"height": 20,
			"seed": 608393217,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "outputs",
			"rawText": "outputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "outputs"
		},
		{
			"type": "text",
			"version": 15,
			"versionNonce": 1793238657,
			"isDeleted": false,
			"id": "fAKhCn1x",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 444.1492906291543,
			"y": 536.3159641412196,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 20,
			"seed": 941136815,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476629345,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "states",
			"rawText": "states",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "states"
		},
		{
			"type": "rectangle",
			"version": 350,
			"versionNonce": 1206412609,
			"isDeleted": false,
			"id": "J8VijzC1wXZRRO-rlDR25",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 232.8514025125561,
			"y": 442.37169641981257,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 344.79763307794514,
			"height": 176.40809591521224,
			"seed": 476919567,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476632343,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 182,
			"versionNonce": 1789821793,
			"isDeleted": false,
			"id": "5xjHoPjHY5k_aQsNBLLHx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 235.71984810861431,
			"y": 626.1823945589961,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"width": 90.70917263972598,
			"height": 19.68880497231737,
			"seed": 1449204353,
			"groupIds": [
				"c8kcDAjBD94RHWGB9zdnr",
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 268,
			"versionNonce": 1073127215,
			"isDeleted": false,
			"id": "LpTxEDXL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 239.3205873300529,
			"y": 626.2084541654376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 84,
			"height": 20,
			"seed": 52037,
			"groupIds": [
				"c8kcDAjBD94RHWGB9zdnr",
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": "[[Mealy FSM]]",
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Mealy FSM",
			"rawText": "Mealy FSM",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Mealy FSM"
		},
		{
			"type": "text",
			"version": 121,
			"versionNonce": 1470721857,
			"isDeleted": false,
			"id": "XuO2izSN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 332.83645299255573,
			"y": 629.0511260315712,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 234,
			"height": 20,
			"seed": 274123695,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "output depends on both input",
			"rawText": "output depends on both input",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "output depends on both input"
		},
		{
			"type": "text",
			"version": 20,
			"versionNonce": 1700323663,
			"isDeleted": false,
			"id": "QuDIjCdO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 236.03828540015894,
			"y": 650.3697829060291,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"width": 147,
			"height": 20,
			"seed": 1435812737,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "and current state",
			"rawText": "and current state",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "and current state"
		},
		{
			"type": "text",
			"version": 548,
			"versionNonce": 1645993761,
			"isDeleted": false,
			"id": "HLzlhrcJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 239.42029060021883,
			"y": 674.2745308065777,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 47,
			"height": 20,
			"seed": 791779649,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "start",
			"rawText": "start",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "start"
		},
		{
			"type": "ellipse",
			"version": 380,
			"versionNonce": 1164828527,
			"isDeleted": false,
			"id": "_DEJ8llhzyTvXyKTfCKLI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 374.92339452983236,
			"y": 690.6156816878921,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 1228953423,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "8HJ8ipEb8zmN7WVwjdbnY",
					"type": "arrow"
				},
				{
					"id": "ww3kocbUm5uiZCloaFEh9",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 333,
			"versionNonce": 2020954881,
			"isDeleted": false,
			"id": "b44sO6pZEni5rougmH-nB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 321.88326983322025,
			"y": 694.8377762519109,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 55.92467171874762,
			"height": 7.46624011713061,
			"seed": 722389281,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "341heJBgtPC73bUvaX0sR",
				"focus": -0.5798182186204285,
				"gap": 5.869549375654589
			},
			"endBinding": {
				"elementId": "pIxFcrCH",
				"focus": -0.773359355601667,
				"gap": 15.631973213763843
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					25.155286368868815,
					-6.0023030947830875
				],
				[
					55.92467171874762,
					1.4639370223475225
				]
			]
		},
		{
			"type": "arrow",
			"version": 422,
			"versionNonce": 1920866703,
			"isDeleted": false,
			"id": "UaV6Zaiy2TYUAHVfmVUqp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 371.9943157155169,
			"y": 718.2797225232152,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 42.33515261433621,
			"height": 7.791821815147614,
			"seed": 1760990575,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "I739j6kf",
				"focus": 1.1849489045791095,
				"gap": 8.440523656979394
			},
			"endBinding": {
				"elementId": "cFFQOreW",
				"focus": -2.682359841232017,
				"gap": 15.774181240923667
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-20.304445962517377,
					7.791821815147614
				],
				[
					-42.33515261433621,
					2.736133168461265
				]
			]
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 255150817,
			"isDeleted": false,
			"id": "qq3PSzsw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 386.21992108223,
			"y": 694.342160142768,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 930807041,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s2",
			"rawText": "s2",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s2"
		},
		{
			"type": "ellipse",
			"version": 428,
			"versionNonce": 566366127,
			"isDeleted": false,
			"id": "341heJBgtPC73bUvaX0sR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 278.87166674601855,
			"y": 691.8405098905772,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 1945482465,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "b44sO6pZEni5rougmH-nB",
					"type": "arrow"
				},
				{
					"id": "JWnyth2IzeFW2KRdybhEo",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 201,
			"versionNonce": 1592477377,
			"isDeleted": false,
			"id": "OwmCvEJs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 292.4087179044907,
			"y": 700.7948980861707,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 15,
			"height": 20,
			"seed": 924140975,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "JWnyth2IzeFW2KRdybhEo",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s1",
			"rawText": "s1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s1"
		},
		{
			"type": "ellipse",
			"version": 395,
			"versionNonce": 1298285007,
			"isDeleted": false,
			"id": "JcRgRlZE5HzJxTK8cSH5r",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 330.0110759277889,
			"y": 746.3740693116816,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 44,
			"height": 40,
			"seed": 2128525263,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "8HJ8ipEb8zmN7WVwjdbnY",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1647756961,
			"isDeleted": false,
			"id": "SmNpGllq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 342.4278790281318,
			"y": 755.7018877715599,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 22,
			"height": 20,
			"seed": 1835315361,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "JWnyth2IzeFW2KRdybhEo",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "s3",
			"rawText": "s3",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "s3"
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 376909807,
			"isDeleted": false,
			"id": "RuU1phPL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 350.67270335856875,
			"y": 724.3173918740764,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 363328641,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "arrow",
			"version": 136,
			"versionNonce": 331827841,
			"isDeleted": false,
			"id": "IZ1T6N_mBEWNtNdz396Bc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 292.67419872716476,
			"y": 741.1670541445545,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 28.106913168329697,
			"height": 24.537828882517147,
			"seed": 1885360143,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "cFFQOreW",
				"focus": 0.921039732806298,
				"gap": 8.476677292683803
			},
			"endBinding": {
				"focus": -0.667062558052497,
				"gap": 9.238130883810786,
				"elementId": "JcRgRlZE5HzJxTK8cSH5r"
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					8.92284686636981,
					14.722710944694086
				],
				[
					28.106913168329697,
					24.537828882517147
				]
			]
		},
		{
			"type": "text",
			"version": 111,
			"versionNonce": 1728666127,
			"isDeleted": false,
			"id": "cFFQOreW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 301.15087601984857,
			"y": 736.7900369326002,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 9944161,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "UaV6Zaiy2TYUAHVfmVUqp",
					"type": "arrow"
				},
				{
					"id": "IZ1T6N_mBEWNtNdz396Bc",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "arrow",
			"version": 343,
			"versionNonce": 1817989729,
			"isDeleted": false,
			"id": "ww3kocbUm5uiZCloaFEh9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 403.6435547633958,
			"y": 737.8581212398785,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 23.525497591357976,
			"height": 22.939168780322234,
			"seed": 1125742127,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "_DEJ8llhzyTvXyKTfCKLI",
				"focus": -0.8767794047185297,
				"gap": 7.953809246699684
			},
			"endBinding": {
				"elementId": "I739j6kf",
				"focus": 2.3427479590886398,
				"gap": 14.077043840006127
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-7.609785034225013,
					14.016321913952424
				],
				[
					-23.525497591357976,
					22.939168780322234
				]
			]
		},
		{
			"type": "text",
			"version": 130,
			"versionNonce": 1410416687,
			"isDeleted": false,
			"id": "0dY59pxT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 373.3140134757577,
			"y": 735.9075589575776,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 771983425,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "UaV6Zaiy2TYUAHVfmVUqp",
					"type": "arrow"
				},
				{
					"id": "ww3kocbUm5uiZCloaFEh9",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "arrow",
			"version": 153,
			"versionNonce": 549805633,
			"isDeleted": false,
			"id": "8HJ8ipEb8zmN7WVwjdbnY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 383.24103996008347,
			"y": 778.1968482172136,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 36.58372661285165,
			"height": 47.73721711989481,
			"seed": 1275648079,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "JcRgRlZE5HzJxTK8cSH5r",
				"focus": 1.3259485450297224,
				"gap": 11.66036570093934
			},
			"endBinding": {
				"elementId": "_DEJ8llhzyTvXyKTfCKLI",
				"focus": -1.301803184879182,
				"gap": 9.202159541134634
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					25.43016802988933,
					-17.399558197012993
				],
				[
					36.58372661285165,
					-47.73721711989481
				]
			]
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 1064788559,
			"isDeleted": false,
			"id": "eVXrTpd9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 414.4710039923779,
			"y": 758.2048830270718,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 2009782305,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "arrow",
			"version": 193,
			"versionNonce": 534900257,
			"isDeleted": false,
			"id": "JWnyth2IzeFW2KRdybhEo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 327.92872157727663,
			"y": 777.9179194453715,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 49.977267832765506,
			"height": 42.99686491486773,
			"seed": 1627846255,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "TMFsBune",
				"focus": 1.0809244533952826,
				"gap": 14.870421844065675
			},
			"endBinding": {
				"elementId": "OwmCvEJs",
				"focus": 2.7031033121341093,
				"gap": 14.457264159979559
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-32.13154006206628,
					-12.213036418299794
				],
				[
					-49.977267832765506,
					-42.99686491486773
				]
			]
		},
		{
			"type": "text",
			"version": 64,
			"versionNonce": 974405743,
			"isDeleted": false,
			"id": "rplIqfAF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 284.6435888942885,
			"y": 763.5586115696693,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 13,
			"height": 20,
			"seed": 1339894785,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "0",
			"rawText": "0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "0"
		},
		{
			"type": "text",
			"version": 70,
			"versionNonce": 1352761857,
			"isDeleted": false,
			"id": "Q9OUxLrU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 446.9797912447968,
			"y": 679.3061867143168,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 47,
			"height": 20,
			"seed": 148656271,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "inputs",
			"rawText": "inputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "inputs"
		},
		{
			"type": "text",
			"version": 63,
			"versionNonce": 632314511,
			"isDeleted": false,
			"id": "3LQOjLsy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 447.3746383070555,
			"y": 701.814532976152,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 63,
			"height": 20,
			"seed": 1043989473,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "outputs",
			"rawText": "outputs",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "outputs"
		},
		{
			"type": "text",
			"version": 67,
			"versionNonce": 268671457,
			"isDeleted": false,
			"id": "0qj4pMq3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 447.76954562371105,
			"y": 725.9024030594145,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 57,
			"height": 20,
			"seed": 1564567215,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "states",
			"rawText": "states",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "states"
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 386150575,
			"isDeleted": false,
			"id": "epO2D7UP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 383.96421701935947,
			"y": 734.4481416760045,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 15,
			"height": 20,
			"seed": 693520801,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/1",
			"rawText": "/1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/1"
		},
		{
			"type": "text",
			"version": 88,
			"versionNonce": 1863824833,
			"isDeleted": false,
			"id": "pIxFcrCH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 341.17596833820403,
			"y": 670.256757836267,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 21,
			"height": 20,
			"seed": 1291332911,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "b44sO6pZEni5rougmH-nB",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/0",
			"rawText": "/0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/0"
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 2008564431,
			"isDeleted": false,
			"id": "Jr6YCmuJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 419.48843228554176,
			"y": 760.0481458486825,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 21,
			"height": 20,
			"seed": 1023567759,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/0",
			"rawText": "/0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/0"
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 821908897,
			"isDeleted": false,
			"id": "TMFsBune",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 292.05829973321096,
			"y": 773.3979608476477,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 21,
			"height": 20,
			"seed": 1077077089,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "JWnyth2IzeFW2KRdybhEo",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/0",
			"rawText": "/0",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/0"
		},
		{
			"type": "text",
			"version": 6,
			"versionNonce": 1751453935,
			"isDeleted": false,
			"id": "wJL3A0qI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 310.5552782109525,
			"y": 738.0162588276814,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 15,
			"height": 20,
			"seed": 514831201,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/1",
			"rawText": "/1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/1"
		},
		{
			"type": "text",
			"version": 12,
			"versionNonce": 149158273,
			"isDeleted": false,
			"id": "I739j6kf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 356.2060774577584,
			"y": 726.7202461801946,
			"strokeColor": "#c92a2a",
			"backgroundColor": "#82c91e",
			"width": 15,
			"height": 20,
			"seed": 1401467215,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "UaV6Zaiy2TYUAHVfmVUqp",
					"type": "arrow"
				},
				{
					"id": "ww3kocbUm5uiZCloaFEh9",
					"type": "arrow"
				}
			],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "/1",
			"rawText": "/1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "/1"
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 1653807887,
			"isDeleted": false,
			"id": "huN2MRj2",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 338.0349876580924,
			"y": 667.4602258809557,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 7,
			"height": 20,
			"seed": 1758703201,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "1",
			"rawText": "1",
			"baseline": 15,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1"
		},
		{
			"type": "rectangle",
			"version": 232,
			"versionNonce": 403382625,
			"isDeleted": false,
			"id": "XexBjpvDWKDGaKwapte0T",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 234.31973042588072,
			"y": 626.3876235176273,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 340.31029691982883,
			"height": 174.06677621849087,
			"seed": 1879884609,
			"groupIds": [
				"k1-FYkhXV5YrEo9D_emCG"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1671476766790,
			"link": null,
			"locked": false
		},
		{
			"id": "WeMFgTpo",
			"type": "text",
			"x": 480.24593895561156,
			"y": 569.3715490476428,
			"width": 61,
			"height": 40,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"seed": 996736289,
			"version": 37,
			"versionNonce": 916071649,
			"isDeleted": false,
			"boundElements": [
				{
					"id": "OrPx4H4SEmcvpkruuCKS1",
					"type": "arrow"
				}
			],
			"updated": 1671476832499,
			"link": null,
			"locked": false,
			"text": " state\ndiagram",
			"rawText": " state\ndiagram",
			"fontSize": 16,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 35,
			"containerId": null,
			"originalText": " state\ndiagram"
		},
		{
			"id": "OrPx4H4SEmcvpkruuCKS1",
			"type": "arrow",
			"x": 477.58177403148534,
			"y": 591.0802705537493,
			"width": 22.20114852595634,
			"height": 10.656558067711899,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"strokeSharpness": "round",
			"seed": 672252975,
			"version": 23,
			"versionNonce": 1605148559,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671476832499,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-22.20114852595634,
					-10.656558067711899
				]
			],
			"lastCommittedPoint": null,
			"startBinding": {
				"elementId": "WeMFgTpo",
				"focus": -0.5088777729221501,
				"gap": 2.6641649241262257
			},
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "triangle"
		},
		{
			"type": "text",
			"version": 46,
			"versionNonce": 1503832335,
			"isDeleted": false,
			"id": "QJb1Gs4t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 503.25065270114374,
			"y": 753.1296884665916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61,
			"height": 40,
			"seed": 1872600303,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "RVC-VaHFeMOvjnlC9Ly-Y",
					"type": "arrow"
				}
			],
			"updated": 1671476845971,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": " state\ndiagram",
			"rawText": " state\ndiagram",
			"baseline": 35,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": " state\ndiagram"
		},
		{
			"type": "arrow",
			"version": 41,
			"versionNonce": 1409190785,
			"isDeleted": false,
			"id": "RVC-VaHFeMOvjnlC9Ly-Y",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 498.2077232915426,
			"y": 775.8760747918035,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 22.20114852595634,
			"height": 10.656558067711899,
			"seed": 1573605327,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": null,
			"updated": 1671476845971,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QJb1Gs4t",
				"focus": -0.5717955533045035,
				"gap": 5.042929409601129
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "triangle",
			"points": [
				[
					0,
					0
				],
				[
					-22.20114852595634,
					-10.656558067711899
				]
			]
		},
		{
			"type": "line",
			"version": 156,
			"versionNonce": 1755473345,
			"isDeleted": false,
			"id": "dFef1EKCZ0oxXZJPDhymC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 4,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -24.2145049534042,
			"y": 616.3502473695293,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 250.0397782160732,
			"height": 0.6025422636940903,
			"seed": 588446369,
			"groupIds": [
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1671477023132,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					250.0397782160732,
					-0.6025422636940903
				]
			]
		},
		{
			"id": "QG7aVZbLggR9n5zGX87of",
			"type": "rectangle",
			"x": -34.185466324702105,
			"y": 625.5566749726478,
			"width": 132.07441220598358,
			"height": 18.645785888467685,
			"angle": 0,
			"strokeColor": "#5c940d",
			"backgroundColor": "#82c91e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"HJkuJMCENbBxL5wD0mn1H",
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "sharp",
			"seed": 104752417,
			"version": 150,
			"versionNonce": 896570063,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671477023132,
			"link": null,
			"locked": false
		},
		{
			"id": "MUN1sLf3",
			"type": "text",
			"x": -30.2979928806987,
			"y": 624.0093720351786,
			"width": 127,
			"height": 20,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"HJkuJMCENbBxL5wD0mn1H",
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "sharp",
			"seed": 1011523489,
			"version": 53,
			"versionNonce": 95552929,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671477023132,
			"link": null,
			"locked": false,
			"text": "state reduction",
			"rawText": "state reduction",
			"fontSize": 16,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "state reduction"
		},
		{
			"id": "xwIiQGOf",
			"type": "text",
			"x": 104.1041946722413,
			"y": 626.8616173457723,
			"width": 125,
			"height": 20,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "sharp",
			"seed": 769046081,
			"version": 24,
			"versionNonce": 1788043503,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671477023132,
			"link": null,
			"locked": false,
			"text": "find all sets of",
			"rawText": "find all sets of",
			"fontSize": 16,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "find all sets of"
		},
		{
			"id": "QhngoH0k",
			"type": "text",
			"x": -32.63163436916809,
			"y": 647.5791660030892,
			"width": 263,
			"height": 100,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "#82c91e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "sharp",
			"seed": 506595585,
			"version": 164,
			"versionNonce": 1132636545,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671477023132,
			"link": null,
			"locked": false,
			"text": "equivalent states: input\nsequences: trigger a transition\nto the same state or equivalent\nstate and generate exactly the\nsame output",
			"rawText": "equivalent states: input\nsequences: trigger a transition\nto the same state or equivalent\nstate and generate exactly the\nsame output",
			"fontSize": 16,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 95,
			"containerId": null,
			"originalText": "equivalent states: input\nsequences: trigger a transition\nto the same state or equivalent\nstate and generate exactly the\nsame output"
		},
		{
			"id": "2JwfslwOSnbtEP90MqIIc",
			"type": "rectangle",
			"x": -34.70339713801741,
			"y": 625.0387046437444,
			"width": 264.14874538079096,
			"height": 121.71561811953109,
			"angle": 0,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [
				"yPclN5Hs3ZL4rLTw1vTTr"
			],
			"strokeSharpness": "sharp",
			"seed": 89972481,
			"version": 276,
			"versionNonce": 712469263,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1671477023132,
			"link": null,
			"locked": false
		},
		{
			"id": "qUKtWwiB",
			"type": "text",
			"x": -406.38082442106327,
			"y": 631.6470929698538,
			"width": 10,
			"height": 20,
			"angle": 0,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"seed": 1688776495,
			"version": 3,
			"versionNonce": 1229517135,
			"isDeleted": true,
			"boundElements": null,
			"updated": 1671476886325,
			"link": null,
			"locked": false,
			"text": "",
			"rawText": "",
			"fontSize": 16,
			"fontFamily": 1,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": ""
		}
	],
	"appState": {
		"theme": "dark",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#5c940d",
		"currentItemBackgroundColor": "transparent",
		"currentItemFillStyle": "cross-hatch",
		"currentItemStrokeWidth": 1,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 1,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 1,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStrokeSharpness": "sharp",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "triangle",
		"scrollX": 292.8188246274383,
		"scrollY": -178.21657740570583,
		"zoom": {
			"value": 0.8689207757978167
		},
		"currentItemLinearStrokeSharpness": "round",
		"gridSize": null,
		"colorPalette": {}
	},
	"files": {}
}
```
%%