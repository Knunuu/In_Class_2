For the PBR shader, it was hard to find the right values and proper textures to get it to look nice. I still don't think it looks that nice, but probably with more time and proper textures, it would look nicer. I could also get a simpler model, and test the different values and textures rather than the figurine I chose.

<img width="364" height="281" alt="Screenshot 2025-10-31 163554" src="https://github.com/user-attachments/assets/ed9658c2-4b18-4944-8737-aff2e3c92a11" />

For the enhaned hologram, I think it matched quite nicely with the model I chose, as it gives it a feeling of a mission briefing in a Sci-Fi video game. I changed the colours, so the main colour is a bit darker, which I think makes it stand out more along with the line effects. There is a couple problems with the model, as the more detailed and thinner parts cause some clipping with the lines.

<img width="324" height="347" alt="Screenshot 2025-10-31 163802" src="https://github.com/user-attachments/assets/fd356555-6f00-46a7-84b2-76a84f18bbd4" />

The texture blending, i did not really have a proper model to use it, but testing with the figurine, it reminded me of invisibility effects of enemies, where they are partially invisible, but still have a sort of outline/reflection so players can see them. This is definently not the intended usage for this shader, but possible with some tweaks, such as having a time effect like the hologram, to have the transparency change, it could look better.

<img width="299" height="343" alt="Screenshot 2025-10-31 163815" src="https://github.com/user-attachments/assets/87f790db-4bca-4bcd-a2b8-546f225202e5" />

The Decal with toggle was kind of confusing for me. Not on how it works, but more on its usage. For cases like this in games, I usually program it by using a seperate object, but I guess this shader can make it more efficient by having it along with the shader, rather than having so many game objects. I fooled around with looking at Guilty Gear Strive 3d Models a year ago, and I didn't understand all the different shaders, but it reminded me that there was a main texture, and without the decals, the entire model was very flat, with the main shader only having the main colours. My decal texture doesn't stand out very well, so maybe there is a way to have it on the front like in an art layer.

<img width="303" height="343" alt="Screenshot 2025-10-31 163830" src="https://github.com/user-attachments/assets/80d2d61e-febc-44e7-9df5-daeb840c8275" />

I still don't realy get why the stencil shader works, but I never thought shaders could intangen with each other. I thought shaders were all independant. It was very interesting seeing the effect of this shader, as you can make things like a window, without having to remodel an entire wall. This shader will be very useful it modeling buildings, but it also allows for games that allow the players to build, to have seamless, realtime windows.

<img width="268" height="269" alt="Screenshot 2025-10-31 163844" src="https://github.com/user-attachments/assets/066d1766-e329-4708-9757-8cf867cc3fff" />
