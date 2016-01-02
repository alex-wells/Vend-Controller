##Vend-Controller

Implementation of a vending machine controller to replace the existing controller in the Snackspace vending machine at Nottinghack.

Software is modeled using QM from www.state-machine.com - this allows us to have quite complex logic running concurrently on a simple
processor such as the arduino. All the code is auto-generated from the model, making it easy to keep the design and source in sync with
each other. Bear in mind though that the generated source files SHOULD NOT be edited by hand, as they will get overwritten when the
model is changed.