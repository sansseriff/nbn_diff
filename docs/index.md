# Index

<h2>Diff-SNSPDs: Packaging, Ordering, and Installation Guide</h2>

![snspd_hero](./attachments/diff_snspd_hero.jpg)

### Tasks

Certain steps of building the differential SNSPDs must happen in order.

```mermaid
graph TD
    G[<a href='./packaging/#shunt-PCB'>Populate shunt PCB</a>] --> B
    EE[<a href='./readout/#apply-solder-mask'>Populate differential Bias-T</a>] --> E[<a href='./readout/#readout'>Prepare readout electronics</a>]
    E --> F[Install in cryostat and test]
    AA[<a href='./mechanics/#detector-packages-with-sapphire-rods'>Order machined differential package and cap</a>] -->A[<a href='./mechanics/#install-sma-ports'>Install SMA ports</a>]
    A --> B[<a href='./packaging/#install-shunt-pcb'>Mount shunt PCB to package</a>]
    B --> C[Install SNSPD in package-mounted ferrule]
    C --> D[Wirebond SNSPD to shunt PCB]
    D --> F
```

<!-- [link to other thing](./packaging/#Other-thing) -->

!!! TODO
Eventually all these steps should have link to explanatory sections.

### Orders

!!! TODO
Pasternack and Digikey orders here
