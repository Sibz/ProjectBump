# ProjectBump
A very basic GoDot game. Networked 3D space flyer where you can only bump into or shoot objects.

This is to prototype a system where:

 * Physics calculations take place on a seperate process over the network
 
 * Game logic, or the authoritive processing of game events take place on a seperate process over the network
 
 * Clients connect to a scene server that relays relevant information from the physics/logic process
 
 * Clients predict physic states and interpolate
