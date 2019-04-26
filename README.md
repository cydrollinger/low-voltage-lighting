
<a href="https://elec-real.com"><img src="/docs/github.png" ></img></a>
>Electronic Realization L.L.C.								   
>Design: Hardware design of 4 LEDs		   
>Engineer: Cy Drollinger								   
>Date: 3/16												           
>Email: cy@elec-real.com								   
>Address: 2023 Stadium Dr Suite 2B #210 Bozeman, MT 59715				   
>Phone: 406-539-8117	

**NOTE:**
 This design has been tested and functions as specified. The design is provided gratis, so, please 
 think critically while utilizing and or redesigning. Open electronic circuitry can be dangerous due 
 to easily shorting circuits which can generate immediate and intense heat resulting in fire. Conversation is
 welcome to improve this design and repository, but, be advised ER is a professional design house and
 monetary compensation is required for additional work toward this design enabling your success.			   
	 
![low voltage lighting](/docs/pictures/headlightV1.6.png)

**PURPOSE:**
Four power LEDs are driven by a timer block from a low voltage supply. The timer block switches the LEDs on
and off the input voltage designed at 3.3v. The brightness of the LEDs is managed by a varying a resistor that
controls the duty cycle, 0-100%, of a 100Hz square wave.
  
>**File Arcitecture with a terse description**


* FOLDERS:
	* docs		: datasheets charging IC and battery holder
	* hardware	: eagle cadsoft(v7.7) hardware design files 	
		* library		: eagle part files 
		* manufacturing	: files required to produce the design
			* bom	: files created to order the parts	
			* gerber	: files generated to manufacture the board
			* <a href="https://oshpark.com/shared_projects/x1jqUElK"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
	
	* readme.md	: this file
	
