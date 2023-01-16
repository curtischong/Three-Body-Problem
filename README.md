# Three-Body-Problem

The Three Body Problem series (Rememberance of Earth's Past) is my favourite sci-fi series of all time. I loved it so much that I wanted to write a simulation of it using the Forward Euler method. Here are a few demo videos of it:

### Trisolaris
https://user-images.githubusercontent.com/10677873/212574777-9f7fed6b-d4cd-4398-a0b1-7bb1457762f4.mov


### Four Body Problem
https://user-images.githubusercontent.com/10677873/212574976-b7487ab9-157c-44a0-ad5c-ec7553a30962.mov


### Almost Equilibrium
This one surprised me the most. You can clearly see how the errors in the forward euler accumulate overtime until the equilibrium breaks
https://user-images.githubusercontent.com/10677873/212575022-a2b403f4-fcdc-47bc-bcdf-bf1eff3be49e.mov

### N-body problem
https://user-images.githubusercontent.com/10677873/212575070-589b9023-d959-4e44-b87b-551c0f7e8846.mov


One thing that I learned was that if you want the system of bodies to remain on-screen, you have to make sure that the sum of all the initial momentums are 0 in all directions. Otherwise, the entire system will slowly drift over to one side and end up off-screen. It was also cool to see some bodies getting ejected from the system.

Oh yeah, I also added a cap on the maximum acceleration a body can undergo in one frame cause when the bodies are really close together, their gravitational pulls are really strong which can cause one body to fly out of the system.
