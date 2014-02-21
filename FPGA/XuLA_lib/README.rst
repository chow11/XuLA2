========================================
XuLA2 Library Files
========================================

These are HDL files for modules that are useful in a variety of larger designs.
(These modules are retained for some legacy projects, but have been superseded by those 
in the VHDL_Lib repository.)

    Audio:
        An interface to an AK4565 audio codec for sampling and generating
        20-bit stereo signals.
        
    ButtonDebounver.vhd:
        A debouncing circuit for a pushbutton.
        
    ButtonScanner.vhd:
        An interface for scanning the button array on the StickIt! Buttons module.

    ClkGen.vhd:
        A clock generator module that uses a DCM to multiply or divide an input clock to create an
        output clock with a higher or lower frequency.

    Common.vhd:
        Contains useful constants and functions.
        
    Fifo.vhd:
        Simple FIFO modules in common-clock and independent-clock versions.

    FlashCntl.vhd:
        A module that provides read/write access to the serial flash device on the XuLA board.
        
    Hcsr04.vhd:
        An interface to an HCSR04 ultrasonic distance sensor.

    HostIo.vhd:
        A set of modules that let a host PC pass data back-and-forth with
        a user design running in the FPGA.
        
    HostIoToI2c.vhd:
        An interface that lets the host PC pass data back-and-forth with
        a chip that has an I2C interface.
        
    HostIoToSpi.vhd:
        An interface that lets the host PC pass data back-and-forth with
        a chip that has an SPI interface.
        
    I2c.vhd:
        A master-to-slave I2C interface.
        
    LedDigits.vhd:
        An interface to the Charlieplexed LED array on the StickIt! LED Digits module.

    MemTest.vhd:
        A module that writes a random stream of values to memory.

    Pwm.vhd:
        A simple pulse-width modulator circuit.
        
    RandGen.vhd:
        An LFSR-based module for generating random values.
        
    RotaryEncoder.vhd:
        An interface to detect CW/CCW rotation of a rotary encoder.
        
    SDCard.vhdl:
        An interface module that simplifies reading/writing to a Secure Digital Flash card.

    SdramCntl.vhd:
        An interface module that makes an SDRAM appear as a simple SRAM-like memory to
        a user design in the FPGA.
        
    Spi.vhd:
        A master-to-slave SPI interface.

    SyncToClk.vhd:
        Modules that sync one or more signals crossing from one clock domain to another.

    TestBoardCore.vhd:
        A module that tests the functioning of a XuLA board by writing a random stream of values into SDRAM
        and then reading it back and comparing it to the original.

    UserInstrJtag.vhd:
        A module that accepts commands and data via the FPGA JTAG port and sends them to modules in the
        FPGA. (Deprecated - superseded by the HostIo modules.)

    Vga.vhd:
        Modules for generating bitmapped and character mapped displays on VGA monitors.
        
    XuLA2.ucf:
        Pin assignments for the XuLA2  board.
        
