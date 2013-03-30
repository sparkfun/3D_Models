Posting 3D Models for most SparkFun Branded PCBs

As 3D printer proliferate over the next few years, it will become increasing handy to have 3D models of the SparkFun products so that you can easily design and print an enclosure to house the electronic bits. We need to begin to model the new and very popular products. Here’s the plan on how to do it.

Here’s the list of stuff we are working on.

Someday soon, there will be a graphic icon on the product page + tick box in Sparkle for anything that has 3D files so that the user knows this thing has 3D files associated with it. This is very similar to Fritzing and Eagle files on product pages.

Process:

    Engineer decides a thing needs a 3D model

    Ticket is created and assigned to Paul, Nick or Nic

    Files get uploaded to github

    Repo gets linked from product page

    Product gets 3D boolean set (once the feature is available)


When posting a 3D model for a product, the file type should be:

    IGS, STL, and SKP (sketchup)

    Scaling at 100x

    Create using Eagle Up, CREO, or any program that can output STL and/or IGS


Filename convention:

    Thing Name SKU.skp

    ex: OpenSegment Serial Display - 20mm COM-11644.skp

    ex: Si4707 Weather Band Receiver Breakout WRL-11129.stl

    Revision ex: Si4707 Weather Band Receiver Breakout WRL-11544.stl


Here are the general rules for deciding if a product needs a 3D model. 1 pt. for each ‘yes’ answer:

    Does the thing pierce the outside wall of an enclosure? (eg: USB connector, SD slot, …)

    Do we build it?

    Is the thing intrinsically portable? (eg: pressure sensor breakout, LiPo battery, ...)

    Do many other competitors offer a similar product?

    Does the thing have flanges?

    Is it an enclosure?

    Does it need a Fritzing model?


Github repos:

    If there is a repo for the overall product (Eagle files, firmware, …), 3D files will live with the product

    If there is no product repo, 3D files will live in the general 3D Model repo

    SparkFun will host a general 3D parts repo for generic parts such as:

        Connectors, IC (ATmega328)

        On/off switches, momentary buttons

        Encoders, potentiometers

        Example starting enclosures

        Servos, motors, steppers


Here are some mechanical details to consider including on the model:

    Anything that sticks out / protrusions greater than a surface mount part

    Mounting holes

    Any identifying text or logos, enough to grock orientation

    Any LEDs

    For extra points and if time allows: pin indicator text, large block ICs


Here are some examples of products that need a 3D mode:

    MPL114A1 : https://www.sparkfun.com/products/9721

    MPU 9150 Breakout : https://www.sparkfun.com/products/11486

    Slide pot : https://www.sparkfun.com/products/11620

    pcDuino


Here are examples of things that do not need a 3D model:

    Arduino Display Module : https://www.sparkfun.com/products/11741

    Wake On Shake : https://www.sparkfun.com/products/11447

    Mr. Roboto

    Propeller Breakout Board : https://www.sparkfun.com/products/11525


Here are some examples of older products that could benefit from 3D models:

    Batteries

    Connectors: USB micro/mini/B, JST 2-pin, barrel

    Displays: 7-segment, 2x16 LCD, monochrome graphic

    Charger products

    Arduino all (Fio, Pro, Pro Mini, Micro)



