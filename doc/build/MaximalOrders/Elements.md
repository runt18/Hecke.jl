<!-- Generated by Docile.jl -->

## Creation

<a name="call(O::Hecke.GenNfOrd, a::Nemo.nf_elem, check::Bool) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:116"></a>

---

```
call(O::GenNfOrd, a::nf_elem, check::Bool = true) -> NfOrderElem
```

> Given an element $a$ of the ambient number field of $\mathcal O$, this function coerces the element into $\mathcal O$. It will be checked that $a$ is contained in $\mathcal O$ if and only if `check` is `true`.


<a name="call(O::Hecke.GenNfOrd, a::Union{Integer,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:134"></a>

---

```
call(O::GenNfOrd, a::Union{fmpz, Integer}) -> NfOrderElem
```

> Given an element $a$ of type `fmpz` or `Integer`, this function coerces the element into $\mathcal O$. It will be checked that $a$ is contained in $\mathcal O$ if and only if `check` is `true`.


<a name="call(O::Hecke.GenNfOrd, arr::Array{Nemo.fmpz,1}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:144"></a>

---

```
call(O::GenNfOrd, arr::Array{fmpz, 1})
```

> Returns the element of $\mathcal O$ with coefficient vector `arr`.


<a name="call{T<:Integer}(O::Hecke.GenNfOrd, arr::Array{T<:Integer,1}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:154"></a>

---

```
call{T <: Integer}(O::GenNfOrd, arr::Array{T, 1})
```

> Returns the element of $\mathcal O$ with coefficient vector `arr`.


<a name="call(O::Hecke.GenNfOrd, a::Nemo.nf_elem, arr::Array{Nemo.fmpz,1}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:166"></a>

---

```
call(O::GenNfOrd, a::nf_elem, arr::Array{fmpz, 1}) -> NfOrderElem
```

> This function constructs the element of $\mathcal O$ with coefficient vector `arr`. It is assumed that the corresponding element of the ambient number field is $a$.


<a name="call(O::Hecke.GenNfOrd) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:176"></a>

---

```
call(O::GenNfOrd) -> NfOrderElem
```

> This function constructs a new element of $\mathcal O$ which is set to $0$.


<a name="zero(O::Hecke.GenNfOrd) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:339"></a>

---

```
zero(O::GenNford) -> NfOrderElem
```

> Returns an element of $\mathcal O$ which is set to zero.


<a name="one(O::Hecke.GenNfOrd) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:347"></a>

---

```
one(O::GenNfOrd) -> NfOrderElem
```

> Returns an element of $\mathcal O$ which is set to one.


## Basic invariants

<a name="parent(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:191"></a>

---

```
parent(a::NfOrderElem) -> GenNfOrd
```

> Returns the order of which $a$ is an element.


<a name="elem_in_nf(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:200"></a>

---

```
elem_in_nf(a::NfOrderElem) -> nf_elem
```

> Returns the element $a$ considered as an element of the ambient number field.


<a name="elem_in_basis(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:213"></a>

---

```
elem_in_basis(a::NfOrderElem) -> Array{fmpz, 1}
```

> Returns the coefficient vector of $a$.


<a name="==(x::Hecke.NfOrderElem, y::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:247"></a>

---

```
==(x::NfOrderElem, y::NfOrderElem) -> Bool
```

> Returns whether $x$ and $y$ are equal.


<a name="deepcopy(x::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:263"></a>

---

```
deepcopy(x::NfOrderElem) -> NfOrderElem
```

> Returns a copy of $x$.


<a name="in(a::Nemo.nf_elem, O::Hecke.GenNfOrd) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:301"></a>

---

```
in(a::nf_elem, O::GenNfOrd) -> Bool
```

> Checks wether $a$ lies in $\mathcal O$.


<a name="den(a::Nemo.nf_elem, O::Hecke.GenNfOrd) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:318"></a>

---

```
den(a::nf_elem, O::GenNfOrd) -> fmpz
```

> Returns the smallest positive integer $k$ such that $k \cdot a$ lies in O.


## Binary and unary operations

<a name="-(x::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:372"></a>

---

```
-(x::NfOrderElem) -> NfOrderElem
```

> Returns the additive inverse of $x$.


```
-(x)
```

Unary minus operator.

<a name="*(x::Hecke.NfOrderElem, y::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:390"></a>

---

```
*(x::NfOrderElem, y::NfOrderElem) -> NfOrderElem
```

> Returns $x \cdot y$.


```
*(x, y...)
```

Multiplication operator. `x*y*z*...` calls this function with all arguments, i.e. `*(x, y, z, ...)`.

<a name="+(x::Hecke.NfOrderElem, y::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:402"></a>

---

```
+(x::NfOrderElem, y::NfOrderElem) -> NfOrderElem
```

> Returns $x + y$.


<a name="-(x::Hecke.NfOrderElem, y::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:414"></a>

---

```
-(x::NfOrderElem, y::NfOrderElem) -> NfOrderElem
```

> Returns $x - y$.


```
-(x, y)
```

Subtraction operator.

<a name="*(x::Hecke.NfOrderElem, y::Union{Integer,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:432"></a>

---

```
*(x::NfOrderElem, y::Union{fmpz, Integer})
```

> Returns $x \cdot y$.


```
*(x, y...)
```

Multiplication operator. `x*y*z*...` calls this function with all arguments, i.e. `*(x, y, z, ...)`.

<a name="+(x::Hecke.NfOrderElem, y::Union{Integer,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:446"></a>

---

```
+(x::NfOrderElem, y::Union{fmpz, Integer})
```

> Returns $x + y$.


<a name="-(x::Hecke.NfOrderElem, y::Union{Integer,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:460"></a>

---

```
-(x::NfOrderElem, y::Union{fmpz, Integer})
```

> Returns $x - y$.


```
-(x, y)
```

Subtraction operator.

<a name="^(x::Hecke.NfOrderElem, y::Union{Int64,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:480"></a>

---

```
^(x::NfOrderElem, y::Union{fmpz, Int})
```

> Returns $x^y$.


```
^(x, y)
```

Exponentiation operator.

<a name="mod(a::Hecke.NfOrderElem, m::Union{Int64,Nemo.fmpz}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:499"></a>

---

```
mod(a::NfOrderElem, m::Union{fmpz, Int}) -> NfOrderElem
```

> Reduces the coefficient vector of $a$ modulo $m$ and returns the corresponding element.


<a name="powermod(a::Hecke.NfOrderElem, i::Integer, m::Nemo.fmpz) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:560"></a>

---

```
powermod(a::NfOrderElem, i::Integer, m::fmpz) -> NfOrderElem
```

> Returns the element $a^i$ modulo $m$.


## Representation matrices

<a name="representation_mat(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:575"></a>

---

```
representation_mat(a::NfOrderElem) -> fmpz_mat
```

> Returns the representation matrix of the element $a$.


<a name="representation_mat(a::Hecke.NfOrderElem, K::Nemo.AnticNumberField) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:590"></a>

```
representation_mat(a::NfOrderElem, K::AnticNumberField) -> FakeFmpqMat
```

> Returns the representation matrix of the element $a$ considered as an element of the ambient number field $K$. It is assumed that $K$ is the ambient number field of the order of $a$.


## Trace and norm

<a name="trace(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:611"></a>

---

```
trace(a::NfOrderElem) -> fmpz
```

> Returns the trace of $a$.


<a name="norm(a::Hecke.NfOrderElem) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:627"></a>

---

```
norm(a::NfOrderElem) -> fmpz
```

> Returns the norm of $a$.


## Random elements

<a name="rand{T<:Union{Integer,Nemo.fmpz}}(O::Hecke.GenNfOrd, R::UnitRange{T<:Union{Integer,Nemo.fmpz}}) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:656"></a>

---

```
rand{T <: Union{Integer, fmpz}}(O::GenNfOrd, R::UnitRange{T}) -> NfOrderElem
```

> Computes a coefficient vector with entries uniformly distributed in `R` and returns the corresponding element of the order.


<a name="rand(O::Hecke.GenNfOrd, n::Integer) at /home/thofmann/.julia/v0.4/Hecke/src/NfMaximalOrder/GenNfOrd.jl:674"></a>

---

```
rand(O::GenNfOrd, n::Union{Integer, fmpz}) -> NfOrderElem
```

> Computes a coefficient vector with entries uniformly distributed in $\{-n,\dotsc,-1,0,1,\dotsc,n\}$ and returns the corresponding element of the order $\mathcal O$.
