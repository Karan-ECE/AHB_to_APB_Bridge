# FPGA-Based AHB-to-APB Bridge Using Verilog HDL, Incorporating Reduced Latency

• Proposed an FPGA-based AHB-to-APB bridge achieving 25% latency reduction (4 → 3 clock cycles) using an optimized
FSM (IDLE, READ, WRITE, R ENABLE, W
ENABLE), enabling one-cycle SETUP and one-cycle ENABLE transfers
while eliminating unnecessary idle transitions.
• Enhanced throughput and power efficiency through early address decoding, support for back-to-back transactions
(transaction overlap), and fine-grain clock gating, ensuring faster peripheral access with reduced delay and lower power
consumption.
