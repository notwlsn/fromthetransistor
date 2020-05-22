Outline of activities for: GeoHot's FromTheTransistor Course https://github.com/geohot/fromthetransistor

This is a personal version of GeoHot's FromTheTransistor course, with the projects and resources that I am currently using to understand the modern computing stack. In contrast to GeoHot's outline, this theoretically builds on real hardware from week 1.

####Section 1: Intro: Cheating our way past the transistor -- 0.5 weeks

1. Buy a basic board
  [[1]](https://www.adafruit.com/product/451 "https://www.adafruit.com/product/451")
  [[2]](https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=593&PartNo=4 "https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=593&PartNo=4") (userman and CDROM)
2. Learn Verilog
  [[1]](http://www.asic-world.com/verilog/veritut.html "http://www.asic-world.com/verilog/veritut.html")
  [[2]](http://www.altera.com/education/training/courses/OHDL1120 "http://www.altera.com/education/training/courses/OHDL1120")
3. Branch out into basic FPGA projects -- Write a device driver?
  [[1]](https://www.fpga4fun.com/ "https://www.fpga4fun.com/")

####Section 2: Bringup: What language is hardware coded in? -- 0.5 weeks

1. Blinking an LED (Verilog, 10)
  [[1]](https://github.com/verilator/verilator "https://github.com/verilator/verilator")
2. Building a UART(Verilog, 100) -- UART, MMIO, Work through serial port, semihosting. Serial test echo program and LED control
