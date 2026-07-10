# BRICKS

A **brick** is an artificial building block of rectangular shape, widely used in masonry construction. Traditionally made from tempered clay that is molded and fired in a kiln, modern engineering also categorizes bricks made from fly ash, concrete, or sand-lime mixtures under the same general classification. 

In India, the standard **modular size** of a conventional brick is **$19 \text{ cm} \times 9 \text{ cm} \times 9 \text{ cm}$**, which becomes **$20 \text{ cm} \times 10 \text{ cm} \times 10 \text{ cm}$** once nominal mortar joints are added.

---

## Uses of Bricks
*   **Load-Bearing Walls:** Supporting vertical weight from roofs and upper floors in low-rise residential configurations.
*   **Infill Partition Walls:** Creating internal partitions in reinforced concrete frame structures.
*   **Pavements & Footpaths:** Providing durable, abrasion-resistant pathways and courtyard flooring.
*   **Retaining Structures:** Building boundary walls, retaining walls, and bridge piers.
*   **Fire-Resistant Lining:** Lining kilns, furnaces, and fireplaces (specifically using fire-clay refractory bricks).

---

## Pros and Cons

### Pros
*   **High Compressive Strength:** Easily withstands heavy vertical, structural loads.
*   **Thermal & Acoustic Insulation:** Dense clay structures absorb solar radiation and damp external sound effectively.
*   **Highly Fire Resistant:** Because they are pre-fired at over $1000^\circ\text{C}$ during manufacturing, they have exceptional natural fire ratings.
*   **Cost-Effective & Local:** Raw materials are abundant, minimizing logistical and production overheads.

### Cons
*   **Low Tensile Strength:** Highly brittle; prone to catastrophic failure under seismic (earthquake) loads unless structurally reinforced.
*   **Time-Consuming Installation:** Lacks modular scale efficiency when compared to large concrete precast blocks or panels.
*   **High Water Absorption Potential:** Inferior quality bricks soak up moisture, causing dampness inside structures and triggering chemical degradation.

---

## Classification per Indian Standards (**IS 1077**)
Under Indian specifications, regular burnt-clay structural bricks are categorized primarily by their minimum compressive strength classes, rather than just traditional qualitative naming conventions. 

| Class Designation (IS 1077) | Minimum Compressive Strength | Water Absorption (% dry weight) | General Field Description |
| :--- | :--- | :--- | :--- |
| **First Class**  | $\ge 35 \text{ N/mm}^2$ (~$350 \text{ kg/cm}^2$) | $< 20\%$ | Perfectly uniform, deep red, metallic ringing sound on impact. No visible flaws. |
| **Second Class** | $15 \text{ to } 20 \text{ N/mm}^2$ | $< 22\%$ | Small superficial cracks allowed. Uniformly burnt; used for interior partition plastering. |
| **Third Class** | $3.5 \text{ to } 7.5 \text{ N/mm}^2$ | $< 25\%$ | Under-burnt, dull brick-red color. Highly porous; restricted to temporary structures. |
| **Fourth Class/ Jhama Bricks** | Variable / Over-burnt | Highly Irregular | Distorted shapes due to over-firing. Extremely hard; crushed to form aggregate for foundations. |

---

## Factors Affecting the Quality of Bricks

### 1. Chemical Composition of Brick Earth
The raw clay must contain well-balanced chemical proportions:
*   **Silica ($50\text{–}60\%$):** Prevents raw bricks from cracking, warping, and shrinking. Excessive silica makes the brick brittle.
*   **Alumina ($20\text{–}30\%$):** Imparts plasticity to the clay so it can be molded. Excess alumina causes heavy shrinkage and cracking during drying.
*   **Lime ($< 5\%$):** Acts as a flux to fuse silica during burning. Excess lime causes the brick to melt and lose its structural shape.
*   **Iron Oxide ($5\text{–}6\%$):** Provides the red color and assists fusion.

### 2. Manufacturing Precision
Improper tempering in pug mills, incomplete drying before entering the kiln, or uneven heat distribution in traditional bull's trench kilns leads to weak, under-burnt cores or brittle, distorted exterior faces.

### 3. Harmful Ingredients (Impurities)
*   **Alkalies:** Cause **efflorescence**—a phenomenon where moisture pulls internal salts to the surface, leaving white powdery deposits that ruin plaster finishes and degrade masonry.
*   **Pebbles & Grits:** Prevent uniform clay mixing, introducing internal structural stress zones that cause erratic cracking.

---

## Properties of an Ideal Brick
To pass rigorous structural requirements on a civil engineering job site, an ideal brick must exhibit the following parameters:

*   **Shape & Color:** True rectangular shape with sharp, square edges and a uniform deep red or copper color.
*   **Size Uniformity:** Standardized dimensions conforming tightly to $19 \times 9 \times 9 \text{ cm}$.
*   **Soundness Test:** Should emit a clear metallic ringing sound when struck against another brick.
*   **Hardness Test:** No permanent scratch mark should remain on the surface when scratched with a fingernail.
*   **Water Absorption Limit:** Must not absorb more than $20\%$ of its dry weight when immersed in clean water for 24 hours.
*   **Crushing Strength:** Must possess a minimal compressive load limit greater than $10.5 \text{ N/mm}^2$ for premium structural implementations.

## Manufacturing of Burnt Clay Brick
<div class="mermaid">
mermaid
%%{init: {
  "theme": "base",
  "flowchart": {
    "useMaxWidth": true,
    "htmlLabels": true,
    "curve": "basis",
    "nodeSpacing": 30,
    "rankSpacing": 45
  },
  "themeVariables": {
    "fontFamily": "Arial, sans-serif",
    "fontSize": "15px",
    "primaryTextColor": "#172033",
    "lineColor": "#475569",
    "background": "#ffffff"
  }
}}%%

flowchart TB

    A["Selection of Clay"]
    B["Unsoiling<br/>Remove top 20–30 cm"]
    C["Digging and Weathering<br/>Duration: 1–2 weeks"]
    D["Blending and Tempering<br/>Add water, sand and additives"]
    E["Pug Mill / Kneading<br/>Homogeneous plastic mass"]

    A --> B --> C --> D --> E

    E --> F{"Moulding"}

    F --> G["Hand Moulding"]
    F --> H["Machine Moulding"]

    G --> G1["Ground Moulding"]
    G --> G2["Table Moulding"]

    H --> H1["Wire-Cut Method"]
    H --> H2["Press-Mould Method"]

    G1 --> I["Drying<br/>3–10 days<br/>Final moisture: 5–7%"]
    G2 --> I
    H1 --> I
    H2 --> I

    I --> I1["Natural Drying<br/>Sunlight / Sheds"]
    I --> I2["Artificial Drying<br/>Hot Air"]

    I1 --> J{"Burning"}
    I2 --> J

    J --> K["Clamp Burning<br/>Temporary method<br/>Duration: 2–6 months"]

    J --> L["Kiln Burning<br/>Bull's Trench Kiln<br/>IS 13954 / IS 13955"]

    L --> L1["Loading Zone"]
    L1 --> L2["Burning Zone<br/>Temperature: 700–1100 °C<br/>Optimum: 900–1000 °C"]
    L2 --> L3["Cooling Zone<br/>Gradual cooling with incoming air"]
    L3 --> L4["Unloading Zone"]

    K --> M["Slow Cooling"]
    L4 --> M

    M --> N["Sorting and Classification<br/>As per IS 1077:1992"]

    N --> O1["Class 1<br/>Strength ≥ 10 N/mm²"]
    N --> O2["Class 2<br/>Strength ≥ 7 N/mm²"]
    N --> O3["Class 3<br/>Strength ≥ 3.5 N/mm²"]

    O1 --> P["Testing<br/>IS 3495 Parts 1–4"]
    O2 --> P
    O3 --> P

    P --> Q["Storage and Dispatch"]

    classDef preparation fill:#FFF4CC,stroke:#B7791F,stroke-width:2px,color:#172033;
    classDef moulding fill:#DBEAFE,stroke:#2563EB,stroke-width:2px,color:#172033;
    classDef drying fill:#DCFCE7,stroke:#15803D,stroke-width:2px,color:#172033;
    classDef burning fill:#FEE2E2,stroke:#DC2626,stroke-width:2px,color:#172033;
    classDef classification fill:#F3E8FF,stroke:#7E22CE,stroke-width:2px,color:#172033;
    classDef finalstage fill:#E0F2FE,stroke:#0369A1,stroke-width:2px,color:#172033;
    classDef decision fill:#FEF3C7,stroke:#D97706,stroke-width:3px,color:#172033;

    class A,B,C,D,E preparation;
    class G,H,G1,G2,H1,H2 moulding;
    class I,I1,I2 drying;
    class K,L,L1,L2,L3,L4,M burning;
    class N,O1,O2,O3,P classification;
    class Q finalstage;
    class F,J decision;
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

