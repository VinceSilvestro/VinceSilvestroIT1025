# Executive Summary # 
This lab explores my findings from researching information systems hardware and ethics. Hardware is not just confined to computers, screens, keyboards, and mice as I initially thought. Components all the way from SSDs to ALUs are very much integral parts of information systems hardware. As these and similar technologies continue to advance at a rapid pace, more people are seriously considering the ethical dilemmas that surround the future of information systems. 

---

# Hardware
- ###  Hard Drives and Memory 
In the performance of a hard drive, latency and transfer rates differ in that latency mainly deals with reading data and transfer rates correspond to writing data. Mechanical latency includes seek time and rotational latency. Seek time is how long it takes a hard drive’s read/write head to find the physical location of a piece of data on the disk; rotational latency is the speed that a region being accessed on a disk rotates into position under a read/write head. Transfer rates, on the other hand, are how fast data is transferred to and from disk media. Latency refers to locating data and transfer rates are associated with moving data.
Unlike a traditional hard drive, an SSD contains no moving parts. In order to read and write information, a regular disk drive’s components must be physically spinning. An SSD is ‘solid’ in the sense that it utilizes flash flash memory, which makes it more stable. Its absence of moving parts makes an SSD faster, too; in fact it has practically no latency at all as with traditional hard drives. 
Increasing RAM makes a computer operate faster. This is because a program must be loaded into RAM before running. Increasing RAM allows more data to be loaded without the added step of first transferring information from the hard drive to the RAM. 
The difference between 64- and 32-bit data paths is that 64-bit data paths transfer 64 bits of data in 1 clock cycle, whereas 32-bit data paths transfer information at half the speed (32 bits of data in 1 clock cycle). 
- ### ALU and the Control Unit 
The ALU is the Arithmetic Logic Unit. It is under the command of the control unit, the so-called captain, both within the CPU. To carry out mathematical operations, the control unit receives instructions from RAM and then tells the ALU what type of operation to perform. When the ALU yields an output, it is carried across its 8 wires to a register. Located inside of the CPU, the register temporarily stores a number. Technically, the register only stores a number if the control unit turns on the register’s set wire. When the system is ready to move a number out of the register and back into the control unit, the control unit turns on the enable wire that also is joined to the register. The register then outputs the value to a CPU bus, which in this case is a group of wires that connect to other registers with their own set and enable wires. The control unit turns on the set wire of the particular register it wants to save that number to.  Finally, the control unit turns off the enable wire from the first register and clear the bus of any signals. In summary, data moves around inside the CPU using the bus, under command of the control unit. The data is stored in each register (eventually making its way to the ALU’s Inputs A and B) in accordance to how it is going to be used. 
- ### CPU, Input & Output
An example of a computer that addresses CPU, input, and output is a self-checkout. First, the checkout uses a scanner to capture the product’s barcode. The machine’s CPU utilizes its own registers and control unit. The CPU processes the input into binary numbers that represent the barcode. These values trigger the product’s price, and other information, to appear on the output device. In this case the output is the self-checkout’s display. 
- ### Logic Gates and Circuits
A logic gate is an electric circuit with two inputs and an output. A truth table is a graphic summarization of a logic gate. It shows the output for every possible input that goes into a logic gate, which are all ones and zeros. Two kinds of logic gates are AND gates and NAND gates. In order for the output of an AND logic gate to be one, both inputs must be one. If either or both of the inputs are zero, AND will output a zero and not a one. By contrast, a NAND logic gate takes the result of an AND gate and simply inverts it. If the result of an AND gate is one, then the result of an AND gate is zero, and vice-versa. 
- ### IEEE 
The purpose of the Institute of Electrical and Electronics Engineers or IEEE is to serve professionals in science, technology, electrical, electronic, and computing fields. The association is dedicated to advancing technology for the benefit of humanity. Ethics are important in device design because as technology becomes increasingly more powerful, it also becomes increasingly easier to abuse. 

---

# Data Representation
- ### Numeric Conversions 
The differences among decimal, binary and hexadecimal numbers relate to each system’s number of bases, or digits. In the decimal system, there are 10 digits, zero through nine. Binary has a base of 2, or in other words, is just ones and zeros. Hexadecimal has sixteen digits in the system: zero through nine, then A through F. Of these three systems, hexadecimal can convey values in the fewest number of digits. It is widely used in HTML programming. 
- ### Hexadecimal Color Representation 
According to colorhexa.com, #ab00ff is magenta in a hexadecimal format. In a RGB color space, #ab00ff is composed of 67.1% red, 0% green and 100% blue. In a CMYK color space, it is composed of 32.9% cyan, 100% magenta, 0% yellow and 0% black. 
When considering accessibility in web sites, this color could be problematic. For those with Protan color blindness, the magenta could appear to look more like blue or even gray. 

---

# Conclusion 
In this lab, I analyzed hardware components like hard drives, RAM, data paths, ALUs, control units, registers, and logic gates. I examined different numbering systems like decimal, binary and hexadecimal. 
Gordon Moore, one of the founders of Intel, recognized that microprocessor transistor counts had been doubling every year in 1965. In 2020, more than ever, it is evident that AI’s ability to influence people can be used for good or bad. Taking into account the speed at which microprocessor technology improves, we must continuously remind ourselves that the technological decisions we make today can and will shape the course of history. 
