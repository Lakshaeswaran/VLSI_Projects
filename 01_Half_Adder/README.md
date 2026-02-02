<h1>Half Adder Implementation using Verilog</h1>

<h2>This project is a hardware implementation of a Half Adder digital circuit using Verilog HDL and simulated in the <a href="https://www.xilinx.com/products/design-tools/vivado.html" title="This link directs to Xilinx Vivado official page">Xilinx Vivado</a> Design Suite.</h2>

This project provides a clean and accurate RTL design of a Half Adder. The fun fact is, you can move from basic logic gates to a professional FPGA simulation environment within a few hours (sounds cool right !!!).

<p>I created this project to bridge the gap between theoretical Boolean logic and practical Hardware Description Language (HDL). I learned the Vivado workflow and Verilog syntax on the fly, focusing on Dataflow modelling and Behavioral simulation.</p>

If you are someone who is curious about VLSI, Digital Electronics, or FPGA development, I highly encourage you to start with this project to understand how code translates into hardware logic.

With that being said, Let's get started !!!

<h2>Requirements:</h2> <ul> <p>Design Suite&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp:&nbspXilinx Vivado</p> <p>Language&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp:&nbspVerilog HDL</ul>

<h2>Project Components:</h2> <p>1. <b>Design Source:</b> The <code>Half_Adder.v</code> file containing the XOR and AND logic using dataflow modeling.</p> 
<img width="1920" height="1080" alt="Screenshot 2026-02-01 185708" src="https://github.com/user-attachments/assets/2ce2661d-d207-4f7d-977e-c2b38d3ce1c5" />
<p>2. <b>Simulation Source:</b> The <code>Half_Adder_TB.v</code> (Testbench) file used to drive input stimuli and verify the truth table.</p> 
<img width="1920" height="1080" alt="Screenshot 2026-02-01 185723" src="https://github.com/user-attachments/assets/ed4c0523-400d-466d-a42d-992da665cd2b" />
  
<p>3. <b>Simulation Waveform:</b> Visual proof of the logic showing the Sum and Carry transitions for all input cases (00, 01, 10, 11).</p>











https://github.com/user-attachments/assets/ae1130b2-d967-451e-b0fd-f6606a4769f8








<h2>Additional Tips:</h2> <p>When viewing your results in Vivado, use the <b>"Zoom Fit"</b> button (or press 'F') to see the entire simulation waveform clearly.</p>


</br> <p>I know, HDL can feel intimidating at the beginning with terms like "Synthesis" and "Implementation." But the simplest way to learn is to write the code and see the waveforms move.</p> <p>If you want to understand the basics of the Vivado workflow, check out this quick guide: <a href="[https://docs.amd.com/r/en-US/ug893-vivado-using-the-ide/Using-the-Vivado-IDE](https://www.amd.com/content/dam/xilinx/support/documents/sw_manuals/xilinx2022_1/ug893-vivado-ide.pdf)">Vivado Design Suite Documentation</a></p>

<h2>Conclusion</h2> <p>I hope you all are eager to get started with digital design.</p>


</br> <p>SO WHAT ARE YOU WAITING FOR? START CODING AND RUN YOUR FIRST SIMULATION!</p> <p>HAPPY CODING !!!</p>
