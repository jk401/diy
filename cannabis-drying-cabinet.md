# Controlled DIY Cannabis Drying Cabinet with Capillary Humidifier

## Project Goal
Create a low-cost, silent drying cabinet maintaining a constant humidity of 60% RH for 14 days (slow & low curing method), focusing on mold prevention and reliable isolation.

---

## Key Specifications (Current Setup)

### 1. Cabinet Construction
- **Material & Dimensions:** 7-layer corrugated cardboard box (dimensions: 120 x 80 x 80 cm, extremely robust, heavy-duty structure, no internal plastic foil needed, utilizes natural humidity-buffering properties of cardboard).
- **Structural Stability:** Due to the heavy 7-layer build, no additional internal wooden frames are required to support the hanging weight.
- **Design Limitations & Odor Note:** *Important:* This cabinet relies on simple, low-cost, silent PC fans (Arctic P14) which lack the high static pressure required to push air through heavy carbon filters (such filters demand expensive, loud 230V growshop inline fans). Consequently, **this setup does NOT filter out cannabis odors**. While ideal for discretion and low cost in controlled spaces, bear in mind that strong herbal aromas will pass through unhindered (though personally, the author considers the pleasant cannabis scent a welcome organic replacement for regular home perfumes! :-)).

### 2. Capillary Humidifier
- **Reservoir & Capacity:** 45l [IKEA Samla box with lid](https://www.ikea.com/sg/en/p/samla-box-with-lid-transparent-s39440767/) ([Samla Box Photo](./cannabis-drying-cabinet-samla-box.jpg)) (57 x 39 x 28 cm), filled with approx. 20 liters of water. This massive 45L total volume / high-capacity design provides immense evaporation performance that vastly outperforms commercial tabletop humidifiers for a fully maintenance-free 14-day run.
- **Principle & Evaporation Media:** Evaporation via capillary wicks using hydroponic non-woven spreader mat ([NFT Spreader Mat 1m x 40cm](https://www.higarden.cz/prislusenstvi-pro-nft/netkana-textilie-spreader-mat-pro-techniku-nft-1m-x-40cm/)).
- **Internal Construction:** Inside the box, the spreader mat is wrapped in a double layer around a spiral-shaped wire mesh/netting, which holds the fabric rigidly together and maximizes the vertical evaporation surface area.
- **Airflow & Lid Configuration:** The lid features two Arctic P14 PWM PST fans blowing air into the box. The box features lateral ventilation holes drilled into the sides, and internal plastic deflectors ensure humid air is smoothly and evenly distributed in all directions (vastly superior to commercial units by preventing direct drafts onto the drying flowers).
- **Water Management & Hygiene:**
  - **Initial Disinfection:** One tablespoon of 3% hydrogen peroxide (H2O2) added during filling to eliminate initial germs from tap water/reservoir.
  - **Long-Term Protection:** Pure stripped copper wire (spiral made from a solid core electrical cable like CYKY) placed on the bottom of the reservoir - the oligodynamic effect of Cu2+ ions reliably prevents algae and slime formation for the full 14 days without chemical additives.

### 3. Ventilation
- **Fans:** **Arctic P14 PWM PST** ([3x 140 mm pressure-optimized fans](https://www.arctic.de/en/P14-PWM-PST/ACFAN00125A/) featuring PWM Sharing Technology (PST) which allows daisy-chaining multiple fans together).
- **Layout & Configuration:**
  - **Humidifier (Samla box):** Equipped with 2 x Arctic P14 fans to efficiently push air across the evaporation wicks.
  - **Main Exhaust:** Equipped with 1 x Arctic P14 fan connected via a 3D-printed reduction (140 mm to 125 mm) into a 125 mm alu-flex exhaust duct ([Aluflex 125mm](https://www.higarden.cz/aluflex/aluflex--prumer-125mm/)).
  - **Passive Intake:** Generous 200 mm alu-flex duct ([Aluflex 200mm, 3m](https://www.higarden.cz/aluflex/aluflex--prumer-200mm/)) ensuring very low resistance and smooth fresh air intake, fitted with an external dust/particle filter made from old nylon stockings stretched over the outside of the 200 mm intake duct.
- **Power & Regulation:** Operated on boosted voltage (approx. 6 to 8 V stepped up from 5V USB using an AliExpress DC-DC step-up converter with a rotary potentiometer knob for precise fan speed adjustment) for whisper-quiet operation and zero airflow draft.

### 4. Climate Control
- **Hygrostat:** Digital hygrostat **XH-W3005** (12V version, 0-99% RH), dedicated exclusively to controlling the humidifier (Samla box fans).
- **Control Logic & Operation:**
  - **Days 1 to 4 (High Evaporation Phase):** Fresh harvest releases massive moisture. The exhaust fan is manually adjusted to a higher speed setting so it continuously removes excess humidity while occasionally balancing out with the humidifier.
  - **Days 5 to 14 (Stabilization Phase):** After the initial drying period, the exhaust fan is turned down to its silent minimum speed, and the XH-W3005 hygrostat takes over completely, running exclusively on the humidifier to maintain the target 60% RH.
- **Power Supply & Regulation:** IKEA SMAHAGEL 3-port USB charger providing 5V DC power, connected via a dedicated [USB to 4Pin PWM Fan Power Adapter Cable with Step-Up Boost](https://www.aliexpress.com/item/1005009180703923.html) (converting USB 5V to adjustable 12V / PWM control for silent fan operation), placed externally outside the drying cabinet.

---

## Estimated Cost Breakdown (Budget)

| Item | Description / Model | Est. Price (EUR) |
| :--- | :--- | :--- |
| **Cardboard Box** | 7-layer robust heavy-duty box (120 x 80 x 80 cm) | 0 EUR (recycled) |
| **Humidifier Box** | IKEA SAMLA 45l box (57 x 39 x 28 cm) | 6 EUR |
| **Fans** | **Arctic P14 PWM PST** (3x 140 mm pressure-optimized fans @ approx. 8 EUR/pc) | 24 EUR |
| **IKEA Power Supply** | IKEA SMAHAGEL 3-port USB charger | 4 EUR |
| **USB Fan Power Adapter** | [USB to 4Pin PWM Step-Up Boost Cable](https://www.aliexpress.com/item/1005009180703923.html) (5V to 12V / PWM) | 4 EUR |
| **Hygrostat** | XH-W3005 digital hygrostat | 6 EUR |
| **Alu-Flex Duct 125mm** | [Aluflex 125mm](https://www.higarden.cz/aluflex/aluflex--prumer-125mm/) (exhaust) | 3 EUR |
| **Alu-Flex Duct 200mm** | [Aluflex 200mm, 3m](https://www.higarden.cz/aluflex/aluflex--prumer-200mm/) (passive intake) | 4 EUR |
| **3D Print Adapter** | 140 mm to 125 mm reduction adapter | 1 EUR |
| **Wicks & Hygiene** | [NFT Spreader Mat 1m x 40cm](https://www.higarden.cz/prislusenstvi-pro-nft/netkana-textilie-spreader-mat-pro-techniku-nft-1m-x-40cm/) + copper wire + H2O2 | 6 EUR |
| **Total Estimated Cost** | | **approx. 58 EUR** |
