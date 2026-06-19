# CEMENT
A cement is a binder used for construction that sets, hardens, and adheres to other materials to bind them together. Cement is seldom used on its own, but rather to bind sand and gravel (aggregate) together. Cement mixed with fine aggregate produces mortar for masonry, or with sand and gravel, produces concrete.

## Manufacturing of Cement

### Dry Process

<div class="mermaid">
flowchart TD

    A[Calcareous Material<br/>Limestone] --> B[Crushing]
    B --> C[Fine Grinding in Ball Mills<br/>and Tube Mills]
    C --> D[Storage]

    E[Argillaceous Material<br/>Clay] --> F[Washing]
    F --> G[Fine Grinding in Ball Mills<br/>and Tube Mills]
    G --> H[Storage]

    D --> I[Mixing in Correct Proportion]
    H --> I

    I --> J[Storage Tank for Raw Mix]
    J --> K[Rotary Kiln]

    L[Coal Dust] --> K

    K --> M[Formation of Clinkers]
    M --> N[Coolers]
    N --> O[Grinding of Clinkers in Ball Mills<br/>and Tube Mills]

    P[Gypsum 2 to 3%] --> O

    O --> Q[Storage in Silos]
    Q --> R[Weighing & Packing in Bags]
    R --> S[Distribution]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>
