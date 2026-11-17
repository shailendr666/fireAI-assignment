# Research: Hostel Floor-wise Waste Volume & Bag Estimation

### 1. Problem Statement

In multi-story student hostels, waste generation across floors is highly volatile—spiking sharply on weekends, post-midnight food deliveries, and exam deadlines. Sanitation workers manually haul waste down staircases with fixed-capacity trolleys or standard 50L plastic sacks without prior visibility into volume. Underestimating volume leads to torn sacks, corridor spillage, and multiple exhausting trips up and down stairs, while overestimating wastes expensive heavy-duty municipal garbage liners.

### 2. Existing Solutions & Why They Fail for Our User

1. **IoT Smart Ultrasonic Bin Sensors (e.g., Libelium / SmartBin)**:
   - _Why it fails_: Commercial IoT smart bin sensors cost ₹2,000–₹5,000 per bin, require stable Wi-Fi/cellular backhaul, battery maintenance, and cannot survive rough handling or liquids in student corridor dustbins.
2. **Municipal Fixed-Route Scheduling (Generic ERP / Municipal Routes)**:
   - _Why it fails_: Municipal collection systems assume steady daily per-capita residential output. They ignore hyper-local student behavior (e.g., Saturday night food delivery container spikes, floor-level party/exam clutter, and absence of elevators).

### 3. Sources Read

1. **CPHEEO Manual on Municipal Solid Waste Management (Ministry of Housing and Urban Affairs, India)**:
   - Examined standard density metrics for institutional and domestic waste (typically 0.2 to 0.4 kg/L for mixed packaging/dry waste).
   - Confirmed that volume/bulk (corrugated food boxes, PET bottles), rather than weight, is the primary operational bottleneck for manual sweepers.
2. **"Solid Waste Management in Educational Campuses" (Journal of Environmental Management)**:
   - Highlighted that hostel corridor bins consist of 60%+ high-volume packaging from e-commerce and late-night food deliveries.
   - Emphasized that predictive sizing of daily collection bags prevents corridor bottlenecking and reduces daily worker transit trips by up to 30%.