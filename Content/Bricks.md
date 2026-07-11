# BRICKS

A **brick** is an artificial building block of rectangular shape, widely used in masonry construction. Traditionally made from tempered clay that is molded and fired in a kiln, modern engineering also categorizes bricks made from fly ash, concrete, or sand-lime mixtures under the same general classification. 

In India, the standard modular size of a conventional brick is 19 cm x 9 cm x 9 cm, which becomes 20 cm x 10 cm x 10 cm once nominal mortar joints are added.

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
*   **Highly Fire Resistant:** Because they are pre-fired at over 1000* C during manufacturing, they have exceptional natural fire ratings.
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
| **First Class**  | >=35 N/mm^2 (approx. 350 Kg/cm^21) | <20% | Perfectly uniform, deep red, metallic ringing sound on impact. No visible flaws. |
| **Second Class** | 15 - 20 N/mm^2 (approx. 150 - 20 Kg/cm^2) | <22% | Small superficial cracks allowed. Uniformly burnt; used for interior partition plastering. |
| **Third Class** | 3.5 - 7.5 N/mm^2 (approx. 35 - 75 Kg/cm^2)  | <25% | Under-burnt, dull brick-red color. Highly porous; restricted to temporary structures. |
| **Fourth Class/ Jhama Bricks** | Variable / Over-burnt | Highly Irregular | Distorted shapes due to over-firing. Extremely hard; crushed to form aggregate for foundations. |

---

## Factors Affecting the Quality of Bricks

### 1. Chemical Composition of Brick Earth
The raw clay must contain well-balanced chemical proportions:
*   **Silica (50 - 60%):** Prevents raw bricks from cracking, warping, and shrinking. Excessive silica makes the brick brittle.
*   **Alumina (20 - 30%):** Imparts plasticity to the clay so it can be molded. Excess alumina causes heavy shrinkage and cracking during drying.
*   **Lime (<5%):** Acts as a flux to fuse silica during burning. Excess lime causes the brick to melt and lose its structural shape.
*   **Iron Oxide (5 - 6%):** Provides the red color and assists fusion.

### 2. Manufacturing Precision
Improper tempering in pug mills, incomplete drying before entering the kiln, or uneven heat distribution in traditional bull's trench kilns leads to weak, under-burnt cores or brittle, distorted exterior faces.

### 3. Harmful Ingredients (Impurities)
*   **Alkalies:** Cause **efflorescence**—a phenomenon where moisture pulls internal salts to the surface, leaving white powdery deposits that ruin plaster finishes and degrade masonry.
*   **Pebbles & Grits:** Prevent uniform clay mixing, introducing internal structural stress zones that cause erratic cracking.

---

## Properties of an Ideal Brick
To pass rigorous structural requirements on a civil engineering job site, an ideal brick must exhibit the following parameters:

*   **Shape & Color:** True rectangular shape with sharp, square edges and a uniform deep red or copper color.
*   **Size Uniformity:** Standardized dimensions conforming tightly to 19 cm x 9 cm x 9 cm.
*   **Soundness Test:** Should emit a clear metallic ringing sound when struck against another brick.
*   **Hardness Test:** No permanent scratch mark should remain on the surface when scratched with a fingernail.
*   **Water Absorption Limit:** Must not absorb more than $20\%$ of its dry weight when immersed in clean water for 24 hours.
*   **Crushing Strength:** Must possess a minimal compressive load limit greater than 10.5 N/mm^2  for premium structural implementations.

## Manufacturing of Burnt Clay Brick

<div class="diagram-container">
  <pre class="mermaid">
    flowchart TD

    A["Selection of Clay"]
    A --> B["Unsoiling<br/>Remove top 20–30 cm"]
    B --> C["Digging and Weathering<br/>1–2 weeks"]
    C --> D["Blending and Tempering<br/>Add water, sand and additives"]
    D --> E["Pug Mill or Kneading<br/>Homogeneous plastic mass"]

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

    I --> I1["Natural Drying<br/>Sunlight or Sheds"]
    I --> I2["Artificial Drying<br/>Hot Air"]

    I1 --> J{"Burning"}
    I2 --> J

    J --> K["Clamp Burning<br/>Temporary process<br/>2–6 months"]

    J --> L["Kiln Burning<br/>Bull's Trench Kiln<br/>IS 13954 and IS 13955"]

    L --> L1["Loading Zone"]
    L1 --> L2["Burning Zone<br/>700–1100 °C<br/>Optimum: 900–1000 °C"]
    L2 --> L3["Cooling Zone<br/>Gradual cooling with incoming air"]
    L3 --> L4["Unloading Zone"]

    L4 --> M["Slow Cooling"]
    K --> M

    M --> N["Sorting and Classification<br/>As per IS 1077:1992"]

    N --> O1["Class 1<br/>Compressive strength ≥ 10 N/mm²"]
    N --> O2["Class 2<br/>Compressive strength ≥ 7 N/mm²"]
    N --> O3["Class 3<br/>Compressive strength ≥ 3.5 N/mm²"]

    O1 --> P["Testing<br/>IS 3495 Parts 1–4"]
    O2 --> P
    O3 --> P

    P --> Q["Storage and Dispatch"]

    %% Colour definitions
    classDef preparation fill:#fff4cc,stroke:#c58b00,stroke-width:2px,color:#222;
    classDef moulding fill:#dbeafe,stroke:#2563eb,stroke-width:2px,color:#222;
    classDef drying fill:#dcfce7,stroke:#15803d,stroke-width:2px,color:#222;
    classDef burning fill:#fee2e2,stroke:#dc2626,stroke-width:2px,color:#222;
    classDef testing fill:#f3e8ff,stroke:#7e22ce,stroke-width:2px,color:#222;

    %% Assign classes to nodes
    class A,B,C,D,E preparation;
    class F,G,H,G1,G2,H1,H2 moulding;
    class I,I1,I2 drying;
    class J,K,L,L1,L2,L3,L4,M burning;
    class N,O1,O2,O3,P,Q testing;
  </pre>
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true, securityLevel: "loose", theme: "default" });
</script>
