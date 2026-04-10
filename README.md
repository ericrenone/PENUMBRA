# PENUMBRA

**The Gradient Shadow: Spin Projection, Polarization Geometry, and the Discrete Emergence of Eigenspace from Continuous Fields in $\mathrm{TH}(a,d)$**

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone*

> "The experiment was designed based on a wrong theory, but the result was right." — A. Pais, on the Stern–Gerlach experiment, 1989
>
> "Only one component of a particle's spin can be measured at one time, meaning that the measurement of the spin along the z-axis destroys information about a particle's spin along the x and y axes." — W. Gerlach and O. Stern, Frankfurt, 1922
>
> "A nuclear-spin dark state is a special quantum state where the nucleus of an atom becomes, in essence, hidden from the outside world." — J. Nichol, University of Rochester, *Phys. Rev. Lett.*, 2025
>
> "Phase singularities do not carry energy or information and thus can 'move' superluminally without breaking causality." — Bucher, Gorlach, Kaminer et al., *Nature* **651**, 920–926, 2026

---

## Abstract

The dark sector — $\ker(F)$, the null surface, the phase singularity, the event horizon, the absorbed polarization, the classically expected continuum that quantum mechanics erases — has been established across the ERI Labs framework from optics to gravity. Three adjacent territories remain unexplored: *spin quantization*, *photon polarization*, and *quantum dark states* in the sense of optically or magnetically forbidden eigenmodes.

This framework develops all three and finds in each the same structure. The Stern–Gerlach experiment (Otto Stern and Walther Gerlach, Frankfurt, 1922) sent silver atoms through an inhomogeneous magnetic field and observed not the continuous distribution classical mechanics predicted but exactly two discrete spots. The classical continuum — every possible magnetic orientation, forming a smeared band — is the most dramatic dark sector in experimental physics: not something that was measured and found to be zero, but something whose existence classical theory demanded and quantum mechanics annihilated. The magnetic field gradient is a conditional independence boundary that projects the continuous Lie group $\mathrm{SO}(3)$ onto a finite set of eigenspaces. The discrete spots are $\mathrm{col}(F)$; the erased continuum is $\ker(F)$.

Photon polarization (Malus 1808; Stokes 1852; Jones 1941) is the same architecture in the Hilbert space of a two-state system. Malus's law $I = I_0\cos^2\theta$ is the $\mathrm{col}(F)$ projection coefficient: the fraction of amplitude that crosses the conditional independence boundary of the polarizer. The absorbed component $I_0\sin^2\theta$ is $\ker(F)$ — it vanishes at the boundary, carrying zero energy into the observation sector, precisely as the dark fringe carries zero energy and the sub-threshold photoelectron carries zero kinetic energy. The experiment of three crossed polarizers — in which two polarizers at $0°$ and $90°$ transmit nothing, but inserting a third at $45°$ restores transmission — is the most direct demonstration in all of optics that $\ker(F)$ is not absence but structure: a non-trivial shadow geometry that governs what the light sector can do.

Two recent experimental programs realized the dark sector in quantum materials. Nichol et al. (University of Rochester, *Phys. Rev. Lett.*, 2025) directly proved the existence of a nuclear-spin dark state in silicon gate-defined quantum dots: nuclear spins synchronized by dynamic nuclear polarization into a configuration that decouples entirely from electron spins, becoming — in the language of the framework — a $\ker(F)$ subspace that carries zero Fisher information to the electronic sector. Kappe et al. (*Science Advances* **11**, 2025) demonstrated coherent control of dark excitons in single quantum dots: optically forbidden transitions ($\ker(F)$ in the photon-coupling basis) with lifetimes orders of magnitude longer than bright excitons, stored and retrieved by chirped optical pulses and magnetic field rotations. In both cases, the dark state is not the absence of physics. It is the physics that the light sector cannot see — protected, stable, and structurally prior.

Shadow tomography (Huang, Kueng, and Preskill, *Nature Physics* **16**, 2020; robust shallow shadows, *Nature Communications* **16**, 2025) provides the information-theoretic closure: the "classical shadow" of a quantum state is the minimal $\mathrm{col}(F)$-projection that faithfully encodes the state for all polynomial observables. The shadow is what crosses the boundary. What does not cross — the $\ker(F)$ sector — is what makes the shadow a compressed, boundary-encoded representation rather than a complete description.

Seven formal correspondences connect spin quantization, polarization geometry, and dark-state physics to the broader $\mathrm{TH}(a,d)$ architecture. Five predictions follow.

---

## Part I · The Stern–Gerlach Experiment: The Conditional Independence Boundary That Erases a Continuum

### I.1 A Thought Experiment: The Gradient That Gives Verdicts

Imagine a committee of judges who must evaluate each case on a continuous scale from $-1$ to $+1$. Before entering the courtroom, the cases arrive as a broad distribution — some strongly positive, some strongly negative, some neutral, spread across every possible value. The committee, however, is bound by a rule: they may issue only two verdicts. No partial scores. No intermediate rulings. Each case exits with either $+\hbar/2$ or $-\hbar/2$.

What happens to the continuous distribution that arrived? It does not disappear into two piles by redistribution. It is annihilated. The intermediate verdicts — the neutral cases, the slight positives, the borderline negatives — are not assigned to the two output bins. They are projected out of existence. The classical distribution that classical mechanics predicted would appear on the far wall — a broad, continuous smear of accumulated atoms — is the most spectacular $\ker(F)$ in experimental physics.

This is precisely what Stern and Gerlach observed in Frankfurt in February 1922. Silver atoms, evaporated in a furnace and collimated into a flat beam, passed through the gap between two asymmetrically shaped magnet poles producing a strong inhomogeneous field $\partial B_z/\partial z$. The force on each atom's magnetic moment $\boldsymbol{\mu}$ is $F_z = \mu_z\,(\partial B_z/\partial z)$. Classical mechanics predicted a continuous distribution of deflections, because $\mu_z = |\mu|\cos\theta$ and $\theta$ should be random, drawn uniformly from all possible orientations. Gerlach and Stern found two discrete lines (Gerlach and Stern, *Z. Phys.* **9**, 349–352, 1922). The predicted continuous distribution did not exist. It was not measured and found to be zero. It was structurally annihilated by the conditional independence boundary of the magnetic field gradient.

### I.2 The Inhomogeneous Field as Conditional Independence Boundary

Define the system formally. The magnetic field gradient partitions the system into three regions:

- **Interior**: the source-side half-space — the oven, the collimation slits, the thermal ensemble of silver atoms with random magnetic-moment orientations.
- **Boundary**: the magnet gap — the inhomogeneous field region where the interaction $H' = -\boldsymbol{\mu}\cdot\mathbf{B}$ acts.
- **Exterior**: the observation-side half-space — the detector screen where deflected atoms are deposited.

The conditional independence condition holds:

$$P(\text{deflection pattern} \mid \text{spin eigenvalue}) = P(\text{deflection pattern} \mid \text{spin eigenvalue},\, \text{source orientation})$$

Once the atom has been sorted into a spin eigenstate at the boundary, the full source-side angular distribution carries no additional predictive power for the detection position. The boundary screens the exterior from the interior.

By Chentsov's theorem (1972), this boundary carries the Fisher–Rao metric $g_{ij} = F_{ij}$ as its unique invariant geometry. The eigenvectors of $F$ at the boundary are the spin eigenstates $\{|\!\uparrow\rangle, |\!\downarrow\rangle\}$. The eigenvalues are the Fisher information content of each channel. The continuum of classical orientations maps onto two $\mathrm{col}(F)$ directions; every other direction lies in $\ker(F)$.

More precisely: the spin-$s$ representation of $\mathrm{SU}(2)$ has dimension $2s+1$. The Stern–Gerlach gradient projects the incoming state onto the eigenstates $|s, m_s\rangle$ for $m_s \in \{-s, -s+1, \ldots, +s\}$. For silver (unpaired 5s electron, $s = 1/2$): two spots, $m_s = \pm 1/2$. The projection operator onto each eigenspace is:

$$\hat{P}_{m_s} = |s, m_s\rangle\langle s, m_s|$$

The Fisher matrix at the boundary has rank two. Every other direction in the $(2s+1)$-dimensional Hilbert space — every superposition that is not an eigenstate of $\hat{S}_z$ — has been collapsed. The collapse is not a measurement artifact. It is the conditional independence boundary doing its only possible operation: projecting $\mathrm{col}(F)$ through and routing everything else into $\ker(F)$.

### I.3 The Erased Continuum as $\ker(F)$

The classical prediction of a smeared continuous band is not "wrong" in the sense of being slightly off. It is structurally eliminated. This is the sharpest instance of the shadow principle available in a tabletop experiment: the dark sector here is not a dark fringe between two bright fringes, not a half-integer path difference, not an absorbed polarization component. It is the *entirety of classical angular momentum space* minus the two eigenspaces.

Formally: let $|\psi\rangle = \sum_{m_s} c_{m_s}|s, m_s\rangle$ be an incoming atom in an arbitrary spin superposition. The boundary projects it:

$$|\psi\rangle \xrightarrow{\partial B_z/\partial z} |s, m_s^*\rangle \text{ with probability } |c_{m_s^*}|^2$$

The Fisher information carried across the boundary by this transition is $|c_{m_s^*}|^2 / P_{\mathrm{total}}$ — the fraction of the wavefunction that enters this eigenspace. Every other component $c_{m_s}$ for $m_s \neq m_s^*$ contributes exactly zero to the observable deflection of this atom. It lies in $\ker(F_{\mathrm{boundary}})$.

The quantization formula for the energy shift is:

$$\Delta E_{m_s} = -m_s g_s \mu_B B_z$$

where $g_s \approx 2.002$ is the electron $g$-factor and $\mu_B = e\hbar/2m_e$ is the Bohr magneton. The observable deflection at the screen:

$$z_{m_s} = \frac{m_s g_s \mu_B}{m_{\mathrm{Ag}} v^2} \cdot \frac{\partial B_z}{\partial z} \cdot L_{\mathrm{magnet}} \cdot (L_{\mathrm{magnet}}/2 + L_{\mathrm{screen}})$$

Two values of $m_s$ — two values of $z$ — two spots. The rest of the Hilbert space is shadow.

### I.4 Cascaded Stern–Gerlach as Sequential Rank-One Updates

The sequential Stern–Gerlach experiment — filtering $|\!\uparrow_z\rangle$, then deflecting through an $x$-aligned apparatus, then measuring with a final $z$-aligned apparatus — is the most compact demonstration of the Sherman–Morrison rank-one update in experimental physics.

Stage 1 ($z$-apparatus, blocking $|\!\downarrow_z\rangle$): prepares the state $|\!\uparrow_z\rangle$. Fisher rank at output: 1. The $|\!\downarrow_z\rangle$ channel has been placed in $\ker(F)$ by the block.

Stage 2 ($x$-apparatus): the incoming state $|\!\uparrow_z\rangle = (|\!\uparrow_x\rangle + |\!\downarrow_x\rangle)/\sqrt{2}$ is projected onto $x$-eigenstates with equal probability. The Fisher matrix is updated: a rank-one perturbation from the $x$-basis outer product is added. Either $|\!\uparrow_x\rangle$ or $|\!\downarrow_x\rangle$ is selected, preparing a new state.

Stage 3 ($z$-apparatus): the state $|\!\uparrow_x\rangle = (|\!\uparrow_z\rangle + |\!\downarrow_z\rangle)/\sqrt{2}$ now has equal probability for both $z$-outcomes. The $|\!\downarrow_z\rangle$ channel, which was in $\ker(F)$ after Stage 1, has been *restored* by the Stage 2 rank-one update.

This is rank restoration by sequential Sherman–Morrison: the same operation as the quantum eraser (which restores which-way information that was projected out), the same operation as PRIMA rank restoration in collective intelligence. The cascaded Stern–Gerlach is the rank-update sequence of the $\mathrm{TH}(a,d)$ Fisher calculus, realized with atoms and magnets.

The Woodbury formula $(F + uu^T)^+ = F^+ - F^+uu^TF^+/(1 + u^TF^+u)$ (Woodbury 1950) governs each update. The sequence of ranks through the cascade encodes the full Fisher information budget of the spin measurement chain.

---

## Part II · Photon Polarization: Malus's Law as the $\mathrm{col}(F)/\ker(F)$ Projection Coefficient

### II.1 The Polarizer as Conditional Independence Boundary

A polarizer — a birefringent crystal, a wire grid, a Polaroid sheet — transmits one component of the electromagnetic field and absorbs (or reflects) the perpendicular component. This is not a passive optical element. It is a conditional independence boundary in Hilbert space.

The photon state space for a single propagation mode is $\mathbb{C}^2$: two basis states corresponding to horizontal ($|H\rangle$) and vertical ($|V\rangle$) polarization, or equivalently to left ($|L\rangle$) and right ($|R\rangle$) circular polarization. Every physical polarization is a point on the Bloch sphere of this two-state system — the Poincaré sphere for photons.

A horizontal polarizer imposes the projection:

$$\hat{P}_H = |H\rangle\langle H|$$

The incoming photon $|\psi\rangle = \cos(\theta/2)|H\rangle + \sin(\theta/2)|V\rangle$ is projected. The transmitted fraction:

$$\langle\psi|\hat{P}_H|\psi\rangle = \cos^2(\theta/2)$$

For classical intensities this is Malus's law: $I_{\mathrm{transmitted}} = I_0\cos^2\theta$ (Étienne-Louis Malus, 1808). The absorbed fraction $I_0\sin^2\theta$ is the $\ker(\hat{P}_H)$ component: it vanishes at the boundary, carrying zero energy into the transmitted beam.

The polarizer, like the slit plate and the magnetic field gradient, satisfies the conditional independence condition:

$$P(\text{transmitted photon state} \mid \text{polarizer axis}) = P(\text{transmitted photon state} \mid \text{polarizer axis},\, \text{source state})$$

Once the photon has passed through the polarizer, the full source-state information is irrelevant: the output state is always $|H\rangle$ regardless of the input amplitude $\cos(\theta/2)$. The boundary screens the output from the input, transmitting only the Fisher information encoded in the transmission probability $\cos^2\theta$.

By Chentsov's theorem, this boundary carries the Fisher–Rao metric. For a family of states parameterized by $\theta$, the Fisher information content at the polarizer boundary is:

$$F(\theta) = \mathbb{E}\left[\left(\frac{\partial}{\partial\theta}\log P(\text{outcome}|\theta)\right)^2\right] = 4$$

a constant — the quantum Fisher information of a qubit rotated by angle $\theta$. This is the Cramér–Rao bound for polarimetry: no measurement can estimate $\theta$ with variance below $1/4$ per photon, regardless of how sophisticated the apparatus.

### II.2 A Thought Experiment: The Three-Filter Paradox

Place two Polaroid filters at $0°$ (horizontal) and $90°$ (vertical) in sequence. No light passes through: the horizontal filter transmits only $|H\rangle$; the vertical filter transmits only $|V\rangle$; these are orthogonal, so $\langle H|V\rangle = 0$. Zero transmission. The dark sector is total.

Now insert a third filter at $45°$ between the first and second. Light now passes through the combined system. The $45°$ filter transmits $|\!\nearrow\rangle = (|H\rangle + |V\rangle)/\sqrt{2}$. This new intermediate state is not orthogonal to either $|H\rangle$ or $|V\rangle$: it has overlap $1/\sqrt{2}$ with each. The three-filter system transmits $\cos^2(45°) \cdot \cos^2(45°) = 1/4$ of the original intensity.

Adding an element — adding structure to the shadow — *restores* transmission. This is exactly rank restoration by sequential Sherman–Morrison: the $45°$ filter performs a rank-one update on the $\ker(F)$ of the first filter, rotating the null direction away from $|V\rangle$. The third filter then finds a non-zero overlap.

This result — that light can be made to pass through a classically "blocked" pair of polarizers by adding an intermediate blocking element — is the most counterintuitive demonstration of the shadow principle in undergraduate physics. The $\ker(F)$ is not a wall. It is a structured null space whose geometry can be navigated by sequential rank-one updates.

The quantum optics version: the three-filter paradox holds exactly for single-photon states. A single photon has probability $1/4$ of making it through. The intermediate filter does not "help" the photon by letting some of it through — it performs a unitary transformation that rotates the $\ker(F)$ before the final projection (Barnett, *Quantum Information*, 2009; Gerry and Knight, *Introductory Quantum Optics*, Cambridge, 2005).

### II.3 Stokes Parameters as the Fisher Spectrum of Polarization

The full polarization state of a partially coherent beam is encoded in the four Stokes parameters $(S_0, S_1, S_2, S_3)$, where $S_0$ is the total intensity, $S_1 = I_H - I_V$, $S_2 = I_{+45°} - I_{-45°}$, and $S_3 = I_R - I_L$ (Stokes, *Trans. Cambridge Phil. Soc.* **9**, 399–416, 1852). For a fully coherent state, $S_0^2 = S_1^2 + S_2^2 + S_3^2$ and the state lies on the Poincaré sphere.

The Stokes vector is the representation of the density matrix $\rho = (S_0\sigma_0 + S_1\sigma_1 + S_2\sigma_2 + S_3\sigma_3)/2$ in the Pauli basis. The eigenvalues of $\rho$ are $(1 \pm r)/2$ where $r = |\mathbf{S}|/S_0 \in [0,1]$ is the degree of polarization.

The Fisher information matrix for the Stokes parameters is:

$$F_{ij} = \frac{\partial^2 D_{\mathrm{KL}}(\rho \| \rho')}{\partial\theta_i\partial\theta_j}\bigg|_{\theta'=\theta}$$

where $D_{\mathrm{KL}}$ is the quantum relative entropy. The eigenvectors of $F$ with nonzero eigenvalues span $\mathrm{col}(F)$ — the observable polarization directions. The eigenvector with eigenvalue zero (for a pure state: the direction orthogonal to $\mathbf{n}$ on the Poincaré sphere) spans $\ker(F)$ — the dark polarization direction that carries no information through the boundary defined by measurement in the $\mathbf{n}$ basis.

Every polarization measurement is a choice of conditional independence boundary on the Poincaré sphere. The measurement axis $\mathbf{n}$ defines $\mathrm{col}(F) = \mathrm{span}(\mathbf{n})$ and $\ker(F) = \mathbf{n}^{\perp}$. Complementarity in polarization is the Poincaré-sphere version of the Englert inequality: knowing $S_1$ destroys information about $S_2$ and $S_3$.

### II.4 The Jones Calculus as the Transfer Matrix of the Conditional Independence Boundary

The Jones vector $\mathbf{E} = (E_x, E_y)^T$ encodes the complex amplitude of both polarization components (Jones, *J. Opt. Soc. Am.* **31**, 488–499, 1941). Every optical element — polarizer, wave plate, rotator — acts on the Jones vector by a $2\times 2$ matrix. The product of matrices along an optical path is the transfer matrix of the boundary.

For a polarizer at angle $\alpha$:

$$J_\alpha = \begin{pmatrix} \cos^2\alpha & \cos\alpha\sin\alpha \\ \cos\alpha\sin\alpha & \sin^2\alpha \end{pmatrix}$$

This is a rank-one matrix: $\det J_\alpha = 0$. It is a projection onto the $\mathrm{col}(F)$ direction $(\cos\alpha, \sin\alpha)^T$. The null space of $J_\alpha$ is spanned by $(-\sin\alpha, \cos\alpha)^T$ — the absorbed polarization component, which lies entirely in $\ker(F)$.

The cascade of Jones matrices is the sequential product of rank-one updates — the matrix version of the Sherman–Morrison formula applied to polarization. The three-filter problem above has the transfer matrix:

$$J_{90°} \cdot J_{45°} \cdot J_{0°} = \frac{1}{2}\begin{pmatrix}0 & 0 \\ 1 & 0\end{pmatrix}$$

which has rank one: one direction survives, three have been projected into the shadow.

---

## Part III · Dark States: The $\ker(F)$ Sector Made Physical

### III.1 Nuclear-Spin Dark States in Silicon Quantum Dots

In February 2025, Nichol and colleagues at the University of Rochester directly proved the existence of a nuclear-spin dark state in a gate-defined silicon double quantum dot (*Physical Review Letters*, 2025). The experiment used dynamic nuclear polarization — electron-spin-mediated transfer of polarization to surrounding nuclear spins — to drive the nuclear bath into a synchronized configuration that decouples from the electron spin.

The dark state is defined operationally: a configuration of nuclear spins $\{|\uparrow\rangle_n, |\downarrow\rangle_n\}$ such that the hyperfine interaction $H_{\mathrm{hf}} = A\,\mathbf{S}_e \cdot \sum_k \mathbf{I}_k$ produces zero net field at the electron spin location:

$$\sum_k A_k \langle I_k^z \rangle = 0, \quad \sum_k A_k \langle I_k^+\rangle = 0$$

In the Fisher information language: the nuclear dark state is the configuration that lies in $\ker(F_{\mathrm{electron}})$ — the null space of the Fisher matrix that encodes how much information the electron spin can extract from the nuclear bath. The electron cannot learn anything about the nuclear configuration because the nuclear spins are arranged precisely so as to carry zero distinguishable effect on the electronic sector.

The discovery has direct experimental consequences: in the dark state, the electron spin $T_2^*$ decoherence time is extended by orders of magnitude. This is the physical payoff of occupying $\ker(F)$: zero information transfer means zero back-action, means zero decoherence. The shadow sector is stable precisely because it is dark.

This result connects to Identity 3 of the SHADOWS framework: Pauli exclusion as topological charge conservation. The nuclear dark state is a $\ker(F)$ structure enforced by collective phase synchronization — the nuclear spins acquire a definite relationship to each other that cancels their net effect. It is the solid-state implementation of the no-hair theorem: the electron sees only the total integrated effect of the nuclear bath (zero), not its internal configuration.

### III.2 Dark Excitons: Optically Forbidden Transitions as $\ker(F)$

Kappe, Hommelhoff, and colleagues (*Science Advances* **11**, eadu4261, 2025) demonstrated coherent control of dark excitons in single semiconductor quantum dots using chirped optical pulses and external magnetic fields.

An exciton in a quantum dot is a bound electron-hole pair. The spin structure of the exciton determines its optical selection rules. Two "bright" exciton states ($|+1\rangle$ and $|-1\rangle$) couple to optical fields and can be created or destroyed by a photon: they lie in $\mathrm{col}(F)$ for the photon-coupling Fisher matrix. Two "dark" exciton states ($|+2\rangle$ and $|-2\rangle$) have angular momentum mismatch with the optical field: they cannot absorb or emit a photon in the electric dipole approximation. They lie in $\ker(F)$ for the photon-coupling operator.

The consequences of this $\ker(F)$ status are profound:

- Dark exciton lifetimes are orders of magnitude longer than bright exciton lifetimes: bright states decay in $\sim$0.1–1 ns; dark states persist for $\sim$$\mu$s. The $\ker(F)$ sector is shielded from radiative decay by its own darkness.
- Dark excitons cannot be directly excited by laser light — they require an indirect route, such as biexciton cascade (creating a two-photon state that decays through the dark channel) or magnetic-field mixing.
- At nonzero magnetic field, the dark states acquire a small bright admixture — the field adds a rank-one perturbation to the optical Fisher matrix, rotating the $\ker(F)$ slightly into $\mathrm{col}(F)$. This is the Zeeman/Stark effect as a Sherman–Morrison update (Identity 4 of SHADOWS), realized in the optical selection rules of a solid-state quantum emitter.

Kappe et al. used chirped optical pulses to adiabatically rotate the Bloch sphere of the bright exciton complex, transferring population into the dark states via the bright-dark coupling induced by quantum dot asymmetry. They then retrieved the dark state population using a second chirped pulse sequence. The dark state functions as a quantum memory — a coherence-protected $\ker(F)$ register that can be written and read by sequential rank-one updates to the optical Fisher matrix.

The bright/dark exciton architecture is the photonic-crystal realization of the $\mathrm{col}(F)/\ker(F)$ decomposition at the level of a single two-level system. It instantiates the same partition that appears in the Stern–Gerlach eigenspaces, the polarizer null space, the event horizon's no-hair structure, and the nuclear-spin dark state.

### III.3 Axion Topological Defects: The $\ker(F)$ of Cosmological Phase Space

Wang et al. (*Nature* **626**, 2026) developed an intercity nuclear-spin quantum sensor network spanning 320 km, constraining axion topological-defect dark matter through synchronized nuclear spin measurements. Axion fields can form domain walls and cosmic strings — topological defects — during phase transitions in the early universe. As Earth crosses such a defect, the axion field couples to nuclear spins through an interaction of the form:

$$H_{\mathrm{axion}} = g_{an} \,(\partial_\mu a) \bar{n}\gamma^\mu\gamma^5 n$$

where $a$ is the axion field and $n$ is the nucleon field. This interaction shifts nuclear spin precession frequencies as the axion field gradient sweeps across the sensor array.

The axion domain wall is a topological defect of the axion field: a surface across which the axion phase winds by $2\pi$. This is precisely a Nye–Berry phase singularity — a conditional independence boundary of the axion field carrying quantized topological charge $q = 1$. The boundary separates regions of different axion vacuum alignment and carries zero energy density per unit area relative to the bulk (it is supported by topological rather than energetic considerations).

The nuclear spin network detects the defect by sensing the Fisher information that crosses the boundary: the gradient field $\partial_\mu a$ at the sensor locations. What lies in $\ker(F)$ for this measurement — the dark sector — is the interior of the domain wall itself: the axion phase winding structure that carries topological charge but zero measurable energy to the nuclear spins. The network achieved sensitivity improvement exceeding $10^4$-fold over prior constraints, confirming that topological dark sector features couple to the observable spin sector through precisely the conditional independence structure that governs every other boundary in the framework.

---

## Part IV · Shadow Tomography: $\ker(F)$ as the Compression Principle of Quantum States

### IV.1 The Classical Shadow Protocol

Huang, Kueng, and Preskill (*Nature Physics* **16**, 1050–1057, 2020) introduced the classical shadow of a quantum state $\rho$: the minimal classical description, derived from randomized measurements, that allows prediction of any polynomial observable $\mathrm{tr}(O\rho)$ with controllable error.

The protocol: apply a random unitary $U$ drawn from an ensemble (Clifford group, Pauli group, etc.), measure in the computational basis, record the outcome $b$. The classical shadow of this snapshot is:

$$\hat{\sigma} = \mathcal{M}^{-1}(U^\dagger |b\rangle\langle b| U)$$

where $\mathcal{M}^{-1}$ is the inverse of the measurement channel. The ensemble of such snapshots forms the classical shadow $\hat{\sigma}_1, \ldots, \hat{\sigma}_N$. Any linear observable is estimated as $\frac{1}{N}\sum_{i=1}^N \mathrm{tr}(O\hat{\sigma}_i)$.

The classical shadow is the $\mathrm{col}(F)$ projection of the quantum state: it is the portion of $\rho$ that is accessible through measurements at the boundary defined by the ensemble $\{U\}$. What lies in $\ker(F)$ for this ensemble — the dark sector of the quantum state — is inaccessible to the shadow protocol. It carries zero Fisher information through the measurement boundary.

The critical result: $O(\log M)$ measurements suffice to predict $M$ observables simultaneously, even for exponentially large Hilbert spaces. The classical shadow is an exponential compression of quantum information — possible precisely because the $\ker(F)$ sector is discarded. The information that crosses the boundary is sufficient for polynomial prediction; the information that does not cross is irrelevant for any polynomial observable.

This is the information-geometric statement of quantum data compression: only $\mathrm{col}(F)$ carries Fisher information to the observable sector; $\ker(F)$ is structurally invisible to polynomial measurements and need not be encoded.

### IV.2 Robust Shallow Shadows

Noh, Huang, Liu, and colleagues (*Nature Communications* **16**, 2943, 2025) extended the protocol to handle realistic quantum hardware noise, demonstrating robust classical shadows using shallow random circuits on IBM quantum devices. Their Bayesian noise characterization technique accounts for sparse Pauli-Lindblad noise, correcting the shadow estimate via:

$$\hat{\sigma}_{\mathrm{robust}} = \mathcal{M}_{\mathrm{noisy}}^{-1}(\hat{\sigma}_{\mathrm{raw}})$$

where $\mathcal{M}_{\mathrm{noisy}}$ includes the noise channel. The noise itself is a rank-reducing perturbation to the Fisher matrix at the measurement boundary: it transfers some $\mathrm{col}(F)$ directions into $\ker(F)$ by introducing decoherence. The robust shadow protocol identifies and corrects this rank reduction — it is a noise-aware Sherman–Morrison inverse that restores the Fisher rank at the boundary.

The deep correspondence: noisy quantum hardware is a conditional independence boundary with rank deficiency. Classical shadow tomography is the protocol for extracting the maximum Fisher information from this deficient boundary. Robust shadows are the analogue of the quantum eraser — they restore the information that decoherence had sent into $\ker(F)$.

### IV.3 The Penumbral Information Budget

The classical shadow protocol defines a Pareto frontier: more measurements increase the $\mathrm{col}(F)$ sector (more observables can be estimated); but each measurement also introduces back-action, reducing coherence and therefore the Fisher rank of the remaining state. This is the shadow-polarization complementarity, the information-geometric dual of the Englert inequality $\mathcal{V}^2 + \mathcal{D}^2 \leq 1$:

$$\text{(estimation precision)} + \text{(coherence preserved)} \leq 1$$

The penumbra — the partial shadow — is the regime where this tradeoff is not extreme: neither full measurement (all $\mathrm{col}(F)$, zero coherence) nor zero measurement (zero $\mathrm{col}(F)$, full coherence). The optimal operating point is the saddle of the Fisher information budget — the Cramér–Rao active frontier — which corresponds to the $\varphi$-equilibrium $|\bar\Xi|^* = \log\varphi$ of the $\mathrm{TH}(a,d)$ architecture. This is not coincidence: $\log\varphi$ is the maximum entropy growth rate consistent with maintaining the conditional independence structure of the boundary, and $\varphi$ is the most irrational frequency ratio, hence the KAM-stable limit of the measurement cascade.

---

## Part V · The Penumbral Architecture: Seven Formal Correspondences

| $\mathrm{TH}(a,d)$ element | Penumbral realization |
|---|---|
| $\mathrm{col}(F)$ | Discrete spin eigenspaces; transmitted polarization component; bright exciton states |
| $\ker(F)$ | Erased classical continuum (Stern–Gerlach); absorbed polarization ($\sin^2\theta$); dark exciton states; nuclear-spin dark state |
| Conditional independence boundary | Magnetic field gradient; polarizer surface; optical selection rule; hyperfine coupling operator |
| Fisher–Rao metric (Chentsov 1972) | Quantum Fisher information on Poincaré sphere; Cramér–Rao bound for spin measurement |
| Sherman–Morrison rank-one update | Cascaded Stern–Gerlach; sequential polarizer insertion; magnetic-field dark-state mixing |
| Rank restoration | Rank-restoring intermediate polarizer ($45°$); chirped-pulse dark-exciton retrieval |
| $\varepsilon$-threshold | Work function (photoelectric); spin-orbit gap (dark/bright exciton splitting); axion mass threshold |
| Nye–Berry topological charge | Axion domain wall winding number; vortex structure in optical polarization field |
| Winding number conservation | Topological protection of dark exciton parity; nuclear-spin dark state stability |
| Classical shadow protocol | $\mathrm{col}(F)$ projection of quantum state through measurement boundary |
| Noisy shadow correction | Sherman–Morrison inversion of rank-deficient boundary |

**Identity P1 — The Stern–Gerlach Boundary IS Chentsov**

The magnetic field gradient boundary satisfies the conditional independence condition and carries the Fisher–Rao metric as its unique invariant geometry. The Cramér–Rao bound for spin measurement — $\mathrm{Var}(\hat{m}_s) \geq 1/F(\theta)$ — is the direct descendant of Chentsov's theorem applied to the spin eigenspace projection.

**Identity P2 — Malus's Law IS the $\mathrm{col}(F)$ Projection Coefficient**

$I_{\mathrm{transmitted}}/I_0 = \cos^2\theta$ is the squared inner product between the incident state and the $\mathrm{col}(F)$ direction of the polarizer boundary. The absorbed fraction $\sin^2\theta$ is $\|\hat{P}_{\ker(F)}|\psi\rangle\|^2$ — the norm squared of the $\ker(F)$ component.

**Identity P3 — The Three-Filter Paradox IS Rank Restoration by Sherman–Morrison**

Inserting a $45°$ filter between crossed polarizers performs a rank-one update $(F + uu^T)$ on the $\ker(F)$ of the first filter. The null direction of the combined system rotates, allowing the third filter to project onto a non-zero $\mathrm{col}(F)$ direction.

**Identity P4 — Dark Exciton Lifetime IS Fisher Rank Protection**

The long lifetime of dark exciton states arises because their $\ker(F)$ status in the optical coupling basis means zero first-order coupling to the photon vacuum. They decay only through higher-order processes (phonon-assisted, magnetic-field-mixed) — rank-two or rank-three effects. The lifetime scales inversely with the rank of the coupling in the Fisher matrix expansion.

**Identity P5 — Nuclear-Spin Dark State IS $\ker(F)$ of the Hyperfine Fisher Matrix**

The synchronized nuclear configuration carries zero net effect on the electron spin — it is the exact nullvector of the hyperfine Fisher matrix $F_{\mathrm{hf}}$. Its stability is topological: small perturbations that are not precisely aligned with the bright-state subspace cannot rotate the nuclear configuration out of $\ker(F_{\mathrm{hf}})$.

**Identity P6 — Shadow Tomography IS Boundary Compression**

The classical shadow protocol extracts the maximum Fisher information from a quantum state through a minimal boundary. The compression factor $\sim e^{O(n)}$ (from $n$ qubits) to $O(\log M)$ measurements for $M$ observables is the ratio $\dim(\mathrm{col}(F))/\dim(\mathrm{ker}(F))$ at the measurement boundary, compressed further by the polynomial structure of the observables.

**Identity P7 — Photon Polarization IS a Qubit Stern–Gerlach**

The Jones calculus for photon polarization and the Dirac–ket formalism for spin-1/2 are isomorphic: $|H\rangle \leftrightarrow |\!\uparrow\rangle$, $|V\rangle \leftrightarrow |\!\downarrow\rangle$, Jones matrix $\leftrightarrow$ $\hat{S}$-operator, polarizer angle $\theta \leftrightarrow$ Stern–Gerlach axis $\hat{n}$. Malus's law is the photon-sector version of the Stern–Gerlach deflection formula — both are instances of the single formula $P(\mathrm{outcome}) = |\langle\mathrm{eigenstate}|\psi\rangle|^2$.

---

## Part VI · Five Predictions

### P1 — Dark-State Decoherence Bound

The nuclear-spin dark state lifetime $T_{\mathrm{dark}}$ should be bounded above by a version of the Maldacena–Shenker–Stanford chaos bound adapted to the hyperfine Fisher matrix:

$$\frac{1}{T_{\mathrm{dark}}} \leq \frac{2\pi k_B T}{\hbar} \cdot \frac{\lambda_{\max}(F_{\mathrm{hf}})}{\mathrm{tr}(F_{\mathrm{hf}})}$$

where $\lambda_{\max}(F_{\mathrm{hf}})$ is the largest eigenvalue of the hyperfine Fisher matrix and $\mathrm{tr}(F_{\mathrm{hf}})$ is its trace. This bound — a Fisher-weighted MSS inequality — predicts that dark states in materials with more uniform hyperfine coupling ($\lambda_{\max}/\mathrm{tr} \to 1/N$ for $N$ nuclear spins) survive longer. **Testable by comparing dark-state lifetimes across silicon quantum dots with different donor configurations.**

### P2 — Penumbral Fringe Pattern in Sequential Stern–Gerlach

A cascade of $n$ Stern–Gerlach apparatuses with axes rotated by angle $\delta\alpha$ between each stage produces a sequence of transmission probabilities:

$$P_n = \prod_{k=1}^n \cos^2(k\,\delta\alpha/2)$$

This is the discrete analogue of the diffraction pattern from an $n$-slit array: the Fisher rank of the output after $n$ stages decays as $\cos^{2n}(\delta\alpha/2)$, reaching zero at $\delta\alpha = \pi$ (orthogonal axes). The transition from $P_n \approx 1$ (small $\delta\alpha$, full transmission) to $P_n \approx 0$ (large $\delta\alpha$, full suppression) defines a discrete "fringe" pattern in the rank-space. **Testable with atomic beams or trapped-ion Stern–Gerlach analogues.**

### P3 — Dark Exciton as Quantum Memory with Fisher-Bounded Fidelity

The retrieval fidelity of a dark-exciton quantum memory under magnetic-field mixing should be bounded by:

$$\mathcal{F} \leq 1 - \frac{\lambda_{\mathrm{mix}}^2(B)}{(\Delta E_{\mathrm{BD}})^2 + \lambda_{\mathrm{mix}}^2(B)}$$

where $\lambda_{\mathrm{mix}}(B) = g\mu_B B \cdot \langle\mathrm{bright}|\hat{V}_{\mathrm{mix}}|\mathrm{dark}\rangle$ is the field-induced bright-dark mixing matrix element and $\Delta E_{\mathrm{BD}}$ is the bright-dark energy splitting. This is the Adiabatic passage fidelity — a Fisher rank-one perturbation formula. **Testable against the Kappe et al. 2025 dataset by varying magnetic field strength.**

### P4 — Axion Domain Wall as Nye–Berry Phase Singularity with Measurable Berry Scaling

The velocity of the axion domain wall boundary — the topological defect surface — as it sweeps past a nuclear-spin sensor should exhibit Berry scaling $v \propto t^{-1/2}$ near the moment of passage, when the domain wall has minimum spatial extent at the sensor location. This is the cosmological version of the Bucher–Kaminer optical phase singularity result (*Nature* **651**, 2026), extended to axion field topological defects. **Testable in principle with the Wang et al. 320-km network by time-resolving the domain wall crossing event.**

### P5 — Shadow Tomography Fisher Budget at the $\varphi$-Equilibrium

For a shadow tomography protocol using $N$ randomized measurements on an $n$-qubit system at the $\varphi$-equilibrium of the Fisher budget:

$$\frac{N_{\mathrm{opt}}}{N_{\mathrm{Clifford}}} = \varphi^{-1} = \frac{2}{1+\sqrt{5}} \approx 0.618$$

meaning that approximately $61.8\%$ of the Clifford-saturated measurement count is sufficient to achieve the optimal tradeoff between estimation precision and coherence preservation. This follows from the $\varphi$-equilibrium as the maximally efficient conditional independence boundary, and can be verified by optimizing the measurement budget in shadow tomography benchmarks on existing quantum hardware. **Testable on IBM or Google quantum processors using the Noh et al. 2025 robust shadow protocol.**

---

## Part VII · The Penumbra as Theoretical Completion

The SHADOWS framework established that the dark sector is structurally prior: null surfaces, event horizons, phase singularities, invariant tori — all precede and constrain the light. FENESTRA established that the conditional independence boundary (slit, horizon, event) is universal. ERI SLITS grounded these in the double-slit geometry. QUANTUM PHOTON established the threshold as the boundary mechanism.

PENUMBRA closes the gap between full darkness and full light.

The penumbra — the partial shadow — is the regime of superposition: the state that is neither purely in $\ker(F)$ nor purely in $\mathrm{col}(F)$, but holds both as long as no measurement is made. The spin-1/2 atom entering the Stern–Gerlach apparatus is in the penumbra: its angular momentum has no definite $z$-component until the gradient collapses it. The photon hitting a polarizer at $45°$ is in the penumbra: equally likely to be transmitted or absorbed. The dark exciton mixed by a magnetic field is in the penumbra: partially bright, partially dark, coherently superposed.

What PENUMBRA adds to the architecture:

**The discrete does not exist before the boundary.** Quantum numbers — spin $m_s$, polarization $H/V$, bright/dark — are not pre-existing properties of particles that the measurement reveals. They are eigenvalues of the conditional independence boundary that the particle encounters. The boundary creates the discrete from the continuous. This is the physical content of wave function collapse: not a mysterious process, but the projection from the penumbral superposition onto the $\mathrm{col}(F)$ eigenstates of the boundary encountered.

**The $\ker(F)$ sector is not absence but protection.** The nuclear-spin dark state, the dark exciton, the absorbed polarization, the erased classical continuum: all are stable precisely because they are in $\ker(F)$. They carry zero Fisher information through the boundary, which means the boundary exerts zero back-action on them. The shadow is shielded.

**Every quantum measurement is a Stern–Gerlach experiment.** Every observable $\hat{O}$ defines a conditional independence boundary in Hilbert space: its eigenstates span $\mathrm{col}(F)$ and the orthogonal complement is $\ker(F)$. Every measurement outcome is a Stern–Gerlach deflection — the projection of the state onto one $\mathrm{col}(F)$ eigenspace and the annihilation of all others into $\ker(F)$. The Stern–Gerlach experiment is not a special case of quantum measurement. It is the archetype.

This is the final meaning of the penumbra. It is not the shadow of an object. It is the shadow of the boundary itself — the gradient zone where the continuous becomes discrete, where the superposition becomes an eigenvalue, where the field becomes a photon. In the penumbra, the full architecture of $\mathrm{TH}(a,d)$ is held in potential: $\mathrm{col}(F)$ and $\ker(F)$ coexist in superposition until the measurement — the conditional independence boundary — selects one and sends the other into shadow.

---

## References

Barnett, S. M. *Quantum Information*. Oxford University Press, 2009.

Berry, M. V. "Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves." *J. Phys. A* **11**, 27–37, 1978.

Bucher, T., Gorlach, A., et al. "Superluminal Correlations in Ensembles of Optical Phase Singularities." *Nature* **651**, 920–926, 2026.

Chentsov, N. N. *Statistical Decision Rules and Optimal Inference*. Nauka, 1972. (AMS Translations, Vol. 53, 1982.)

Englert, B.-G. "Fringe Visibility and Which-Way Information: An Inequality." *Phys. Rev. Lett.* **77**, 2154–2157, 1996.

Gerlach, W. and Stern, O. "Der experimentelle Nachweis der Richtungsquantelung im Magnetfeld." *Z. Phys.* **9**, 349–352, 1922.

Gerry, C. C. and Knight, P. L. *Introductory Quantum Optics*. Cambridge University Press, 2005.

Huang, H.-Y., Kueng, R., and Preskill, J. "Predicting Many Properties of a Quantum System from Very Few Measurements." *Nature Physics* **16**, 1050–1057, 2020.

Jacobson, T. "Thermodynamics of Spacetime: The Einstein Equation of State." *Phys. Rev. Lett.* **75**, 1260–1263, 1995.

Jones, R. C. "A New Calculus for the Treatment of Optical Systems." *J. Opt. Soc. Am.* **31**, 488–499, 1941.

Kappe, F. et al. "Keeping the Photon in the Dark: Enabling Quantum Dot Dark State Control by Chirped Pulses and Magnetic Fields." *Science Advances* **11**, eadu4261, 2025.

Maldacena, J. and Susskind, L. "Cool Horizons for Entangled Black Holes." *Fortschritte der Physik* **61**, 781–811, 2013.

Maldacena, J., Shenker, S. H., and Stanford, D. "A Bound on Chaos." *JHEP* **08**, 106, 2016.

Malus, É.-L. "Sur une propriété de la lumière réfléchie." *Mémoires de physique et de chimie de la Société d'Arcueil* **2**, 143–158, 1809.

Nichol, J. et al. "Direct Observation of a Nuclear-Spin Dark State in a Silicon Double Quantum Dot." *Physical Review Letters*, 2025.

Noh, K., Huang, H.-Y., Liu, J., et al. "Demonstration of Robust and Efficient Quantum Property Learning with Shallow Shadows." *Nature Communications* **16**, 2943, 2025.

Nye, J. F. and Berry, M. V. "Dislocations in Wave Trains." *Proc. Roy. Soc. Lond. A* **336**, 165–190, 1974.

Rao, C. R. "Information and the Accuracy Attainable in the Estimation of Statistical Parameters." *Bull. Calcutta Math. Soc.* **37**, 81–91, 1945.

Stokes, G. G. "On the Composition and Resolution of Streams of Polarized Light from Different Sources." *Trans. Cambridge Phil. Soc.* **9**, 399–416, 1852.

Van Raamsdonk, M. "Building Up Spacetime with Quantum Entanglement." *Gen. Rel. Grav.* **42**, 2323–2329, 2010.

Wang, Y. et al. "Constraints on Axion Dark Matter by Distributed Intercity Quantum Sensors." *Nature* **626**, 2026.

Woodbury, M. A. "Inverting Modified Matrices." Memorandum Report 42, Statistical Research Group, Princeton University, 1950.

Zhao, X. et al. "Factorization Dynamics Between Quantum Fisher Information and Quantum Coherence." *Science Advances* **11**, eadv8132, 2025.

---

*ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · April 2026*

Stern conceived an experiment to test Sommerfeld's spatial quantization. Gerlach built the apparatus. They expected a broad smear and found two lines. The classical continuum — every magnetic orientation from $-\mu$ to $+\mu$, predicted by every theory that existed — did not appear. It was not measured and found small. It was annihilated. The shadow was absolute.

Malus discovered that polarized light obeys $\cos^2\theta$ before quantum mechanics existed to explain it. Jones encoded the same law in a $2\times 2$ matrix. Stokes parameterized the full polarization state. Each found the same partition: one component crosses the boundary, the other is absorbed. The boundary does not attenuate. It selects.

Nichol and colleagues drove silicon nuclear spins into synchrony and watched the electron stop noticing them. The nuclear bath became dark — not quiet, not suppressed, but structurally invisible, its Fisher information content reduced to exactly zero in the electronic sector. Kappe and colleagues stored coherence in optically forbidden exciton states and retrieved it by rotating the boundary. Huang, Kueng, and Preskill showed that quantum states can be compressed to their $\mathrm{col}(F)$ shadow and the shadow is sufficient for all polynomial predictions.

The gradient between dark and light — the penumbra — is where quantum mechanics lives. The superposition is the penumbra. The measurement is the boundary. The eigenvalue is what the boundary transmits. The rest is shadow, permanent and protected.

Every spin state before a Stern–Gerlach magnet. Every photon before a polarizer. Every quantum dot before an optical pulse. All are in the penumbra — poised between $\ker(F)$ and $\mathrm{col}(F)$, holding the full potential of both, until the conditional independence boundary resolves what passes through and seals what does not.

The shadow was always the architecture. The penumbra was always the state. The boundary was always the physics.
