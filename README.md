**1. Generation Protocol and Computational Constraints**

To facilitate the generation of synthetic BUS images, please refer to the technical specifications outlined in the attached PDF. To maintain system stability and prevent ResourceExhaustedError exceptions, it is recommended to process generation in batches.

Technical Recommendation: A batch size of approximately 4,000 samples per iteration is suggested to optimize throughput while staying within hardware resource limits.

**2. Quality Assurance and Resolution**

Each synthetic output is generated at a fixed resolution of 256x256 pixels. Users must account for these resolution constraints when evaluating image clarity or integrating them into high-fidelity datasets. Furthermore, as these images are synthetically derived, inherent artifacts or stochastic noise may be present.

**3. Clinical Validation Requirements**

Formal clinical validation is mandatory prior to any practical application. To ensure the morphological integrity of the data:

  a) A certified radiologist should be consulted to review and curate the generated samples.

  b) Expert oversight is required to differentiate viable diagnostic proxies from images containing significant synthetic noise.

**Disclaimer regarding Clinical Use**

The developers and providers of this tool assume no liability for any diagnostic or clinical decisions made based on these synthetic samples. All generated data must be subject to independent medical oversight; use of these images without professional verification is strictly at the user's risk.
