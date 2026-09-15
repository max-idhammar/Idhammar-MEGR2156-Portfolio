# A4 – [Motor Mount]

[Download CAD File Here](https://drive.google.com/file/d/1ESdYk73eGihqRNLd0DPVW8H0vUqbO9EC/view?usp=sharing)

## Objective

The objective of this project is to design a wall-mounted motor mount for a 24 V DC gear motor that safely supports a 300 N applied load. We needed to use beam bending equations to determine the geometry of the beam. Finally We had to create FBDs and a CAD model of the motor mount.

## Analyze

I decided to use PLA for my material, it has a yield strength of 50 Mpa which becomes an allowable 16.8 Mpa with a safety factor of 3

### FBD 1
<img width="1125" height="460" alt="Screenshot 2026-09-15 072959" src="https://github.com/user-attachments/assets/b66a77e9-355f-4c93-af84-d833a4ff9916" />

### Feature 2
<img width="1722" height="933" alt="Screenshot 2026-09-15 072720" src="https://github.com/user-attachments/assets/8a3f3d1b-88e4-4a70-9a59-a99077b188c5" />

### FBD 2
<img width="581" height="727" alt="Screenshot 2026-09-15 073149" src="https://github.com/user-attachments/assets/3975ae84-b42f-4163-8333-76f026eccc10" />

## Decide

### Parametric Equation
<img width="1057" height="852" alt="Screenshot 2026-09-15 033941" src="https://github.com/user-attachments/assets/2d739bb8-7de6-4d45-a6ca-892e9e791479" />
Using my calculations I set up a series of parametric equations to ensure my motor mount would pass all requirements given. I do think I made a bit too many variables however the ones not in use did not affect my final model.

### Starting The CAD Model
<img width="630" height="511" alt="Screenshot 2026-09-15 034148" src="https://github.com/user-attachments/assets/53974234-456f-40f5-93d0-99690f532de6" />
I started with a basic square shape for the motor to rest on and for the shaft to pass through.

### First Extrusion
<img width="1243" height="765" alt="Screenshot 2026-09-15 034341" src="https://github.com/user-attachments/assets/4f7bdb46-2d47-4906-b21c-7ec0d903d3d7" />

### Added Wall Mount Piece
<img width="848" height="722" alt="Screenshot 2026-09-15 035223" src="https://github.com/user-attachments/assets/9294bf70-885b-4229-96b1-2b248c2279d5" />
This piece will mount to the wall and will have ribs to support against deflection.

### Putting Mounting Bolts In
<img width="1656" height="1030" alt="Screenshot 2026-09-15 045143" src="https://github.com/user-attachments/assets/4c4febf0-b367-46a1-af2b-78d2a35ba6ca" />
Using the diameter given to us from dimensions I placed 4 evenly spaced holes sized for clearance.

### Small Indent Needed
<img width="1161" height="852" alt="Screenshot 2026-09-15 050045" src="https://github.com/user-attachments/assets/4dc57a9a-d4cd-45bd-8dcb-96de42285d89" />
The motor has a small extrusion smaller than the diameter of the motor but larger than the shaft, this also requires a clearance. 

### Added Hole For Motor Shaft
<img width="1138" height="871" alt="Screenshot 2026-09-15 050225" src="https://github.com/user-attachments/assets/afae49e0-e49a-4c0d-b6d3-5d5b23a1e44c" />
I made a hole for the shaft to pass through.

### Wall Mounting Holes + Threads
<img width="1133" height="825" alt="Screenshot 2026-09-15 052432" src="https://github.com/user-attachments/assets/a34b4b5c-2ef1-42d1-b7e0-ff5482c3e329" />
Since the mount is using bolts I made the holes threaded, and kept the same diameter spacing for the wall mounting screws.

### Adding Ribs
<img width="885" height="586" alt="Screenshot 2026-09-15 055335" src="https://github.com/user-attachments/assets/fe136e15-0d04-4f8d-b861-f3ee34bc0194" />
In order to minimize deflection I decided to add ribs on either end of the wall mount side of my mount. 

### Finished Isometric View
<img width="772" height="570" alt="Screenshot 2026-09-15 055619" src="https://github.com/user-attachments/assets/0e991cac-c779-4a59-b313-35c3f7853efe" />
The finished Motor mount has clearances on all holes, used parametric modeling for the geometry and has ribs to minimize deflection

## Communicate

Using ribbing helped with deflection and my parametric equations helped me design the part, I also used parametric equations for the clearance holes required. The paper on motor mount design was helpful for getting a starting point and general guidelines.

### Appendix

(Motor Mount Design Paper From UFL)[https://web.mae.ufl.edu/designlab/Lab%20Assignments/EML2322L%20Motor%20Mount%20Design.pdf]
