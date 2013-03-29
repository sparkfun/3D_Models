3D_Models
=========

3D Models of our products

Needs 3D model:

    (Retired) UDB4 : https://www.sparkfun.com/products/10582

    (Nic B) MPL114A1 : https://www.sparkfun.com/products/9721

    (Nic B) MPU 9150 Breakout : https://www.sparkfun.com/products/11486

    (Nick P) Slide pot : https://www.sparkfun.com/products/11620

    (Paul) pcDuino


Doesn’t need 3D model:

    Arduino Display Module : https://www.sparkfun.com/products/11741

    Wake On Shake : https://www.sparkfun.com/products/11447

    Mr. Roboto

    Propeller Breakout Board : https://www.sparkfun.com/products/11525



Here are the general rules for selecting products for needing a 3D model. 1 pt. for each ‘yes’ answer:

    Does the thing pierce the outside wall of an enclosure?

    Do we build it?

    Is the thing intrinsically portable? (eg: pressure sensor breakout, LiPo battery, ...)

    Do many other competitors offer a similar product?

    Anything with flanges

    Anything with a Fritzing model

    Is it an enclosure?



Not new products we should consider modeling:

    Batteries

    Connectors: USB micro/mini/B, JST 2-pin, barrel

    Displays: 7-segment, 2x16 LCD, monochrome graphic

    Charger products

    Arduino all (Fio, Pro, Pro Mini, Micro)



When posting a 3D model for a product, the file type should be?

    STL, IGS, possibly DAE (collata)

    Scaling at 100x?

    Create using Eagle Up, CREO, or any program that can output STL and/or IGS


Graphic icon + tick box for anything that has 3D files.

Github repos:

    3D files live with the product repo

    SparkFun hosts a general 3D parts repo for generic parts such as:

        Connectors, IC (ATmega328)

        On/off switches, momentary buttons

        Encoders, potentiometers

        Example starting enclosures

        Servos, motors, steppers


Level of quality:

    Anything that sticks out / protrusions greater than a surface mount part

    Mounting holes

    Any identifying text or logos, enough to grock orientation

    Any LEDs

    Extra if time allows: pin indicator text, large block ICs


How to get dimensions of a board:

    Export Eagle files to a DXF

    Use calipers to verify

    Do a 1:1 print of 3D model and compare to physical object
