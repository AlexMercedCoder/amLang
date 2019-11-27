# amLang
### Spec by Alex Merced of AlexMercedCoder.com


## classes

```
///creating a class

Dog <: {CLASS}
    ///constructor
    con(parameter)
        this.variable <: parameter

    ///method
    myMethod(parameter)
        print('woof')


/// instantiating a class instance

sparky <: {Dog(value)}

sparky.myMethod(value)

/// interitance

Shitzu <: {CLASS <: Dog}
    ///override myMethod
    myMethod(parameter)
        print('yap')


```
