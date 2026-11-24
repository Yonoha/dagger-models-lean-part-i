# Part I: declaration and provenance index

This index accompanies the concise English PDF. It retains the declaration names,
source locations and per-result provenance from the previous catalogue.
Its prose and grouping are AI-generated. The PDF gives the mathematical statements;
this index supplies the longer implementation references.

All source links are fixed to proof-source commit [`9ee62295a79ef61269259e27216afc0292458931`](https://github.com/Yonoha/dagger-models-lean-part-i/tree/9ee62295a79ef61269259e27216afc0292458931).
The statements, hypotheses and Lean proof sources are unchanged by this editorial revision.

The 40 grouped results reference 88 distinct declarations in 56 source files.
Including the separately credited reused foundations gives 91 declarations
in 58 files, as in the earlier catalogue.

The machine-readable counterpart is [results.json](results.json).

<a id="result-1-1"></a>

## Result 1.1

Title in the PDF: `A: the dagger Bergner model structure`.

**Lean declarations**

- `DaggerComparator.mainA`

**Source files**

- `lean/MainTheoremsA.lean`: [line 11](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/MainTheoremsA.lean#L11).
- `lean/ChallengeTheoremA.lean`: [line 42](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeTheoremA.lean#L42).

**Construction and reuse**

Theorem A of Part I, including the model classes, generating data, trivial-fibration criterion, and left properness for the same model structure. The ordinary Kan--Quillen foundations are reused.

<a id="result-1-2"></a>

## Result 1.2

Title in the PDF: `B: the dagger Joyal model and its Quillen equivalence`.

**Lean declarations**

- `DaggerComparator.mainB`

**Source files**

- `lean/MainTheoremsBCD.lean`: [line 14](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/MainTheoremsBCD.lean#L14).
- `lean/ChallengeActualMainTheoremB.lean`: [line 17](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeActualMainTheoremB.lean#L17), [line 25](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeActualMainTheoremB.lean#L25).

**Construction and reuse**

Theorem B of Part I. The comparison uses the original dagger lift of ordinary rigidification and the same standard dagger Joyal model appearing in the model-structure statement.

<a id="result-1-3"></a>

## Result 1.3

Title in the PDF: `C: intrinsic recognition of dagger Joyal equivalences`.

**Lean declarations**

- `DaggerComparator.originalMainTheoremC`

**Source files**

- `lean/MainTheoremsBCD.lean`: [line 18](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/MainTheoremsBCD.lean#L18).
- `lean/ChallengeOriginalMainTheoremC.lean`: [line 14](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeOriginalMainTheoremC.lean#L14), [line 19](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeOriginalMainTheoremC.lean#L19), [line 23](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeOriginalMainTheoremC.lean#L23), [line 27](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeOriginalMainTheoremC.lean#L27).

**Construction and reuse**

Theorem C of Part I. The statement applies to every dagger morphism between dagger quasi-categories and relates local weak equivalences to unitary essential surjectivity.

<a id="result-1-4"></a>

## Result 1.4

Title in the PDF: `D: the anti-involutive model and the comparison obstruction`.

**Lean declarations**

- `DaggerComparator.mainD`

**Source files**

- `lean/MainTheoremsBCD.lean`: [line 22](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/MainTheoremsBCD.lean#L22).
- `lean/ChallengeActualMainTheoremD.lean`: [line 11](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ChallengeActualMainTheoremD.lean#L11).

**Construction and reuse**

Theorem D of Part I, together with the construction of the precise source model used in the formal statement. The obstruction concerns these specified models and adjunctions.

<a id="result-2-1"></a>

## Result 2.1

Title in the PDF: `Presheaves on the reversal simplex category`.

**Lean declarations**

- `DaggerModels.nonempty_daggerSSetEquivalencePresheaf`

**Source files**

- `lean/DaggerModels/Presheaf.lean`: [line 384](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/Presheaf.lean#L384).

**Construction and reuse**

The equivalence is constructed for the dagger simplicial sets of Part~I; it is not an existing Mathlib equivalence invoked under a new name.

<a id="result-2-2"></a>

## Result 2.2

Title in the PDF: `Local finite presentability of dagger simplicial sets`.

**Lean declarations**

- `DaggerModels.daggerSSetLocallyFinitelyPresentable`
- `DaggerModels.daggerSSetLocallyPresentable`

**Source files**

- `lean/DaggerModels/Presentable.lean`: [line 75](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/Presentable.lean#L75), [line 83](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/Presentable.lean#L83).

**Construction and reuse**

The preceding project-specific presheaf equivalence transports Mathlib's presentability results for presheaf categories without changing the universe of values.

<a id="result-2-3"></a>

## Result 2.3

Title in the PDF: `The free dagger simplicial-set adjunction`.

**Lean declarations**

- `DaggerModels.exists_freeDaggerAdjunction`

**Source files**

- `lean/DaggerModels/FreeDagger.lean`: [line 57](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDagger.lean#L57).

**Construction and reuse**

A left Kan extension along the ordinary-simplex inclusion into the reversal simplex category, transported through the presheaf equivalence, gives the original forgetful functor its left adjoint. The explicit pushout description is the separate result below.

<a id="result-2-4"></a>

## Result 2.4

Title in the PDF: `Free completion as a pushout over the zeroth skeleton`.

**Lean declarations**

- `DaggerModels.freeDagger_pushout`
- `DaggerModels.freeDagger_skeleton_pushout`

**Source files**

- `lean/DaggerModels/FreeDaggerPushout.lean`: [line 312](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDaggerPushout.lean#L312).
- `lean/DaggerModels/FreeDaggerSkeleton.lean`: [line 19](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDaggerSkeleton.lean#L19).

**Construction and reuse**

The common vertices, both inclusions, the adjunction unit, and the dagger interchange equations are constructed together.

<a id="result-2-5"></a>

## Result 2.5

Title in the PDF: `Images of monomorphisms under free completion`.

**Lean declarations**

- `DaggerModels.freeDagger_map_freeCofibration`

**Source files**

- `lean/DaggerModels/FreeDaggerCofibration.lean`: [line 194](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDaggerCofibration.lean#L194).

**Construction and reuse**

The proof uses the concrete pushout and positive-dimensional nondegenerate simplices. The conclusion concerns the specified free-cofibration predicate.

<a id="result-2-6"></a>

## Result 2.6

Title in the PDF: `Free-boundary cell presentation of free cofibrations`.

**Lean declarations**

- `DaggerModels.exists_relativeFreeBoundaryCellComplex`
- `DaggerModels.freeBoundarySaturation_eq`

**Source files**

- `lean/DaggerModels/RelativeCellPresentation.lean`: [line 91](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/RelativeCellPresentation.lean#L91), [line 99](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/RelativeCellPresentation.lean#L99).

**Construction and reuse**

The relative skeletal filtration and its attaching pushouts give the cell presentation; individual closure lemmas are subsumed here.

<a id="result-2-7"></a>

## Result 2.7

Title in the PDF: `Free cofibrations need not be normal monomorphisms`.

**Lean declarations**

- `DaggerModels.DaggerSSet.exists_freeCofibration_not_normalMono`

**Source files**

- `lean/DaggerModels/NormalCofibrationObstruction.lean`: [line 143](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/NormalCofibrationObstruction.lean#L143).

**Construction and reuse**

The counterexample uses the map from the initial object to the point object. It makes no general assertion about the cofibration classes of two model structures.

<a id="result-2-8"></a>

## Result 2.8

Title in the PDF: `Ordinary equivalence need not be unitarily essentially surjective`.

**Lean declarations**

- `DaggerModels.UnitaryObstruction.exists_equivalence_not_unitarilyEssentiallySurjective`

**Source files**

- `lean/DaggerModels/UnitaryObstruction.lean`: [line 168](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/UnitaryObstruction.lean#L168).

**Construction and reuse**

A concrete two-object integer dagger groupoid supplies the example. The cited declaration does not include subsequent claims about nerves or weak equivalences.

<a id="result-2-9"></a>

## Result 2.9

Title in the PDF: `Free dagger simplicial categories`.

**Lean declarations**

- `DaggerModels.exists_freeDaggerSimplicialCategory`
- `DaggerModels.FreeDaggerSimplicialCategory.exists_freeDaggerSimplicialCategoryAdjunction`

**Source files**

- `lean/DaggerModels/FreeDaggerSimplicialCategory.lean`: [line 115](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDaggerSimplicialCategory.lean#L115), [line 106](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeDaggerSimplicialCategory.lean#L106).

**Construction and reuse**

The free category is built explicitly from finite paths and their simplicial mapping sets.

<a id="result-2-10"></a>

## Result 2.10

Title in the PDF: `Monadicity over dagger simplicial graphs`.

**Lean declarations**

- `DaggerModels.DaggerSimplicialCat.forgetGraph_monadic`

**Source files**

- `lean/DaggerModels/DaggerSimplicialMonadicity.lean`: [line 92](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSimplicialMonadicity.lean#L92).

**Construction and reuse**

The free adjunction, reflection of isomorphisms, and graph-split coequalizers are established in the formalization before applying Mathlib's Beck theorem. This is distinct from forgetting to ordinary simplicial categories.

<a id="result-2-11"></a>

## Result 2.11

Title in the PDF: `Dagger simplicial graphs as presheaves`.

**Lean declarations**

- `DaggerModels.exists_daggerGraphPresheafEquivalence`
- `DaggerModels.daggerGraphLocallyFinitelyPresentable`
- `DaggerModels.daggerGraphHasLimits`
- `DaggerModels.daggerGraphHasColimits`

**Source files**

- `lean/DaggerModels/DaggerGraphPresheaf.lean`: [line 36](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerGraphPresheaf.lean#L36).
- `lean/DaggerModels/DaggerGraphPresentable.lean`: [line 27](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerGraphPresentable.lean#L27), [line 19](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerGraphPresentable.lean#L19), [line 23](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerGraphPresentable.lean#L23).

**Construction and reuse**

The index category and equivalence encode endpoints, simplicial edges, and reversal. Presentability and completeness follow by transport from Mathlib's presheaf results.

<a id="result-2-12"></a>

## Result 2.12

Title in the PDF: `Finitarity of the free-word monad`.

**Lean declarations**

- `DaggerModels.DaggerSimplicialCat.exists_finitary_freeDaggerSimplicialCategoryAdjunction`

**Source files**

- `lean/DaggerModels/FreeWordFinitary.lean`: [line 135](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/FreeWordFinitary.lean#L135).

**Construction and reuse**

The proof analyzes actual finite paths and endpoint pullbacks. It asserts finitarity for this particular monad, not for arbitrary monads.

<a id="result-2-13"></a>

## Result 2.13

Title in the PDF: `Local finite presentability of dagger simplicial categories`.

**Lean declarations**

- `DaggerModels.daggerSimplicialCatHasLimits`
- `DaggerModels.daggerSimplicialCatHasColimits`
- `DaggerModels.daggerSimplicialCatLocallyFinitelyPresentable`
- `DaggerModels.daggerSimplicialCatLocallyPresentable`

**Source files**

- `lean/DaggerModels/DaggerSimplicialPresentable.lean`: [line 16](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSimplicialPresentable.lean#L16), [line 19](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSimplicialPresentable.lean#L19), [line 23](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSimplicialPresentable.lean#L23), [line 28](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSimplicialPresentable.lean#L28).

**Construction and reuse**

Colimits are constructed through semantic quotients of mapping spaces; finitely presentable free-graph generators then give the presentability criterion. This result does not assert a model structure.

<a id="result-2-14"></a>

## Result 2.14

Title in the PDF: `Creation of limits and colimits by ordinary forgetting`.

**Lean declarations**

- `DaggerModels.DaggerSimplicialCat.forget_createsLimits`
- `DaggerModels.DaggerSimplicialCat.forget_createsColimits`

**Source files**

- `lean/DaggerModels/DaggerOrdinaryCreation.lean`: [line 14](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerOrdinaryCreation.lean#L14), [line 17](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerOrdinaryCreation.lean#L17).

**Construction and reuse**

This construction concerns forgetting to ordinary simplicial categories, rather than the monadic forgetful functor to dagger simplicial graphs.

<a id="result-2-15"></a>

## Result 2.15

Title in the PDF: `Two-object free cells and finite presentability`.

**Lean declarations**

- `DaggerModels.exists_twoObjectDaggerCell`
- `DaggerModels.exists_finitelyPresentable_twoObjectDaggerCell`

**Source files**

- `lean/DaggerModels/TwoObjectDaggerCellUniversal.lean`: [line 22](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/TwoObjectDaggerCellUniversal.lean#L22).
- `lean/DaggerModels/TwoObjectCellPresentability.lean`: [line 58](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/TwoObjectCellPresentability.lean#L58).

**Construction and reuse**

The cell and its universal property are constructed directly; the finite-presentability conclusion uses Mathlib's result for finite simplicial sets under the stated extra hypothesis.

<a id="result-2-16"></a>

## Result 2.16

Title in the PDF: `Small colimits of ordinary simplicial categories`.

**Lean declarations**

- `DaggerModels.simplicialCatHasColimits`

**Source files**

- `lean/DaggerModels/SimplicialColimits.lean`: [line 160](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SimplicialColimits.lean#L160).

**Construction and reuse**

The construction uses free paths and semantic quotients of simplicial mapping sets. It also supplies colimits needed for the ordinary rigidification below.

<a id="result-2-17"></a>

## Result 2.17

Title in the PDF: `Ordinary rigidification, the coherent nerve, and opposites`.

**Lean declarations**

- `DaggerModels.OrdinaryRigidification.rigidification_coherentNerve_adjunction`
- `DaggerModels.OrdinaryRigidification.coherentNerve_iso_mathlib`
- `DaggerModels.OrdinaryRigidification.rigidification_simplex_iso`
- `DaggerModels.OrdinaryRigidification.RigidificationOpposite.rigidificationOppositeIso`
- `DaggerModels.OrdinaryRigidification.RigidificationOpposite.rigidificationOppositeIso_coherence`

**Source files**

- `lean/DaggerModels/OrdinaryRigidification.lean`: [line 130](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/OrdinaryRigidification.lean#L130), [line 135](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/OrdinaryRigidification.lean#L135), [line 140](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/OrdinaryRigidification.lean#L140).
- `lean/DaggerModels/RigidificationOpposite.lean`: [line 149](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/RigidificationOpposite.lean#L149), [line 165](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/RigidificationOpposite.lean#L165).

**Construction and reuse**

The construction uses Mathlib's simplex thickening and presheaf Kan-extension API; the natural nerve and opposite comparisons, including coherence, are proved here. These are ordinary simplicial-categorical results.

<a id="result-2-18"></a>

## Result 2.18

Title in the PDF: `Dagger rigidification and its adjunction`.

**Lean declarations**

- `DaggerModels.OrdinaryRigidification.DaggerRigidification.daggerRigidification`
- `DaggerModels.OrdinaryRigidification.DaggerRigidification.daggerRigidification_forget`
- `DaggerModels.OrdinaryRigidification.DaggerAdjunction.daggerRigidificationCoherentNerveAdjunction`
- `DaggerModels.OrdinaryRigidification.DaggerAdjunction.adjunction_unit`
- `DaggerModels.OrdinaryRigidification.DaggerAdjunction.adjunction_counit`

**Source files**

- `lean/DaggerModels/DaggerRigidification.lean`: [line 117](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerRigidification.lean#L117), [line 128](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerRigidification.lean#L128).
- `lean/DaggerModels/DaggerAdjunction.lean`: [line 76](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerAdjunction.lean#L76), [line 89](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerAdjunction.lean#L89), [line 96](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerAdjunction.lean#L96).

**Construction and reuse**

The dagger lift retains the full ordinary enriched mapping data. The adjunction alone does not assert a Quillen equivalence.

<a id="result-2-19"></a>

## Result 2.19

Title in the PDF: `The Kan dagger core and the unitary core of a Kan object`.

**Lean declarations**

- `DaggerOriginalDaggerCoreKan.daggerCoreCandidate_kan`
- `DaggerOriginalDaggerCoreKan.daggerCore_isGreatestKanSubcomplex`
- `DaggerNativeOriginalKanUnitaryCanonicalIso.unitaryCanonicalIso`

**Source files**

- `lean/OriginalDaggerCoreKan.lean`: [line 24](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalDaggerCoreKan.lean#L24), [line 32](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalDaggerCoreKan.lean#L32).
- `lean/NativeOriginalKanUnitaryCanonicalIso.lean`: [line 37](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeOriginalKanUnitaryCanonicalIso.lean#L37).

**Construction and reuse**

The core construction and Kan property are established for the specified inner-horn hypothesis; the unitary-core isomorphism requires the additional Kan hypothesis.

<a id="result-3-1"></a>

## Result 3.1

Title in the PDF: `Small object argument for finitely presentable domains`.

**Lean declarations**

- `DaggerModels.SmallObjectFiniteDomains.hasSmallObjectArgument`

**Source files**

- `lean/DaggerModels/SmallObjectFiniteDomains.lean`: [line 56](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SmallObjectFiniteDomains.lean#L56).

**Construction and reuse**

A general bridge proved in this formalization and applied to Mathlib's small object argument. The three universes and the smallness, colimit, and finite-presentability hypotheses remain explicit.

<a id="result-3-2"></a>

## Result 3.2

Title in the PDF: `Boundary-cell presentations and lifting for simplicial sets`.

**Lean declarations**

- `DaggerModels.SSetBoundaryCells.exists_relativeCellComplex`
- `DaggerModels.SSetBoundaryCells.boundaryCells_eq_monomorphisms`
- `DaggerModels.SSetBoundaryCells.I_rlp_eq_monomorphisms_rlp`
- `DaggerModels.SSetBoundaryFibration.boundary_rlp_le_fibrations`

**Source files**

- `lean/DaggerModels/SSetBoundaryCells.lean`: [line 28](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SSetBoundaryCells.lean#L28), [line 44](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SSetBoundaryCells.lean#L44), [line 55](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SSetBoundaryCells.lean#L55).
- `lean/DaggerModels/SSetBoundaryFibration.lean`: [line 159](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/SSetBoundaryFibration.lean#L159).

**Construction and reuse**

A boundary-cell construction and its lifting consequences proved here for ordinary simplicial sets, using Mathlib's boundary inclusions and Kan-fibration predicate.

<a id="result-3-3"></a>

## Result 3.3

Title in the PDF: `Promotion of a local-presentability rank`.

**Lean declarations**

- `DaggerLocallyPresentableRankPromotion.locallyPresentable_of_le`

**Source files**

- `lean/LocallyPresentableRankPromotion.lean`: [line 9](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/LocallyPresentableRankPromotion.lean#L9).

**Construction and reuse**

A general proposition proved here using Mathlib's strong-generator criterion. Pullbacks and the regularity of both cardinals are retained as hypotheses.

<a id="result-3-4"></a>

## Result 3.4

Title in the PDF: `Detection of weak equivalences by a localization`.

**Lean declarations**

- `DaggerNativeAllCofibrantLocalizationSaturation.weakEquivalence_iff_localization_isIso`

**Source files**

- `lean/NativeAllCofibrantLocalizationSaturation.lean`: [line 32](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeAllCofibrantLocalizationSaturation.lean#L32).

**Construction and reuse**

A general detection theorem proved here. It assumes an existing model structure and localization; it does not construct a Bousfield localization.

<a id="result-3-5"></a>

## Result 3.5

Title in the PDF: `Local finite presentability of simplicial and bisimplicial sets`.

**Lean declarations**

- `DaggerNativeSSetLocallyPresentable.locallyFinitelyPresentable`
- `DaggerNativeBisimplicialLocallyPresentable.locallyFinitelyPresentable`

**Source files**

- `lean/NativeSSetLocallyPresentable.lean`: [line 17](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeSSetLocallyPresentable.lean#L17).
- `lean/NativeBisimplicialLocallyPresentable.lean`: [line 14](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeBisimplicialLocallyPresentable.lean#L14).

**Construction and reuse**

Concrete applications in this formalization of Mathlib's results on presheaf categories and strong generators. They supply ambient-category hypotheses for the small object and Smith constructions.

<a id="result-3-6"></a>

## Result 3.6

Title in the PDF: `Functorial factorizations for the specified generators`.

**Lean declarations**

- `DaggerModels.DaggerSmallObject.generators_hasFunctorialFactorization`
- `DaggerFixedCategorySmallObject.I_hasFunctorialFactorization`
- `DaggerFixedCategorySmallObject.J_hasFunctorialFactorization`

**Source files**

- `lean/DaggerModels/DaggerSmallObject.lean`: [line 51](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/DaggerModels/DaggerSmallObject.lean#L51).
- `lean/FixedCategorySmallObject.lean`: [line 31](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/FixedCategorySmallObject.lean#L31), [line 35](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/FixedCategorySmallObject.lean#L35).

**Construction and reuse**

Concrete applications of the general small object argument after finite presentability is proved for the relevant domains. These factorizations alone do not identify a weak-equivalence class or establish a model structure.

<a id="result-3-7"></a>

## Result 3.7

Title in the PDF: `A model structure on fixed-object strict dagger groupoids`.

**Lean declarations**

- `DaggerOriginalFixedObjectStrictDaggerModel.strictDaggerModel`
- `DaggerOriginalFixedObjectStrictDaggerModel.model_weakEquivalence_iff`
- `DaggerOriginalFixedObjectStrictDaggerModel.model_fibration_iff`

**Source files**

- `lean/OriginalFixedObjectStrictDaggerModel.lean`: [line 20](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectStrictDaggerModel.lean#L20), [line 24](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectStrictDaggerModel.lean#L24), [line 30](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectStrictDaggerModel.lean#L30), [line 35](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectStrictDaggerModel.lean#L35).
- `lean/OriginalFixedObjectDaggerCategories.lean`: [line 87](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectDaggerCategories.lean#L87), [line 91](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalFixedObjectDaggerCategories.lean#L91).

**Construction and reuse**

A concrete model structure established here after the required factorizations are proved. The fixed-object category retains the original dagger enrichment and strictness. This theorem does not establish the simplicial model axioms or all of Theorem C.

<a id="result-3-8"></a>

## Result 3.8

Title in the PDF: `Generation of normal monomorphisms by boundaries in all degrees`.

**Lean declarations**

- `DaggerModels.OriginalAntiInvolutiveNormalGeneratorRecognition.normalMonos_eq_normalGeneratorSaturation`
- `DaggerModels.OriginalAntiInvolutiveNormalGeneratorRecognition.normalMono_mem_transfinite_pushouts`

**Source files**

- `lean/OriginalAntiInvolutiveNormalGeneratorRecognition.lean`: [line 164](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalAntiInvolutiveNormalGeneratorRecognition.lean#L164), [line 127](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalAntiInvolutiveNormalGeneratorRecognition.lean#L127).

**Construction and reuse**

A concrete generation theorem proved here with the original normality predicate and free boundary maps in all degrees, rather than a positive-degree substitute.

<a id="result-3-9"></a>

## Result 3.9

Title in the PDF: `Construction of the ordinary Joyal model structure`.

**Lean declarations**

- `DaggerNativeOriginalJoyalSmithModelData.modelData`
- `DaggerNativeOriginalJoyalSmithModelData.generated_left_eq`
- `DaggerNativeOriginalJoyalSmithModelData.generated_right_eq`
- `DaggerActualDCHRightInducedAndMainTheoremD.ordinaryJoyalModel`

**Source files**

- `lean/NativeOriginalJoyalSmithModelData.lean`: [line 12](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeOriginalJoyalSmithModelData.lean#L12), [line 25](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeOriginalJoyalSmithModelData.lean#L25), [line 29](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/NativeOriginalJoyalSmithModelData.lean#L29).
- `lean/ActualDCHRightInducedAndMainTheoremD.lean`: [line 45](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualDCHRightInducedAndMainTheoremD.lean#L45).

**Construction and reuse**

A concrete Smith application assembled here for ordinary simplicial sets, not a new proof of a general Smith recognition theorem. It supplies the ordinary model used in the next comparison.

<a id="result-3-10"></a>

## Result 3.10

Title in the PDF: `The anti-involutive Joyal model and its right-induced classes`.

**Lean declarations**

- `DaggerActualOriginalAntiJoyalSmithModelData.modelData`
- `DaggerActualDCHRightInducedAndMainTheoremD.model`
- `DaggerActualDCHRightInducedAndMainTheoremD.cofibration_iff_normal`
- `DaggerActualDCHRightInducedAndMainTheoremD.weakEquivalence_iff_underlying`
- `DaggerActualDCHRightInducedAndMainTheoremD.fibration_iff_underlying`

**Source files**

- `lean/ActualOriginalAntiJoyalSmithModelData.lean`: [line 20](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualOriginalAntiJoyalSmithModelData.lean#L20).
- `lean/ActualDCHRightInducedAndMainTheoremD.lean`: [line 15](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualDCHRightInducedAndMainTheoremD.lean#L15), [line 22](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualDCHRightInducedAndMainTheoremD.lean#L22), [line 56](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualDCHRightInducedAndMainTheoremD.lean#L56), [line 64](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualDCHRightInducedAndMainTheoremD.lean#L64).

**Construction and reuse**

A concrete Smith application in the anti-involutive category and an identification of right-induced weak equivalences and fibrations relative to the constructed ordinary Joyal model. This is the existence component of the model used in Theorem D.

<a id="result-4-1"></a>

## Result 4.1

Title in the PDF: `A Kan--Quillen self-equivalence from $Q_{\mathrm{rc}}$`.

**Lean declarations**

- `DaggerActualQQuillenEquivalence.isQuillenEquivalence`
- `DaggerActualQKanCounitWeakEquivalence.counit_weakEquivalence`

**Source files**

- `lean/ActualQQuillenEquivalence.lean`: [line 17](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualQQuillenEquivalence.lean#L17).
- `lean/ActualQKanCounitWeakEquivalence.lean`: [line 24](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualQKanCounitWeakEquivalence.lean#L24).

**Construction and reuse**

The construction and comparison for the original right-cone object $Q_{\mathrm{rc}}$ are proved in this formalization, using the existing Kan model structure and Mathlib's Quillen-equivalence criterion. This is an ordinary simplicial-set result, distinct from the dagger rigidification result in Theorem B.

<a id="result-4-2"></a>

## Result 4.2

Title in the PDF: `The projective model structure on simplicial $C_2$-actions`.

**Lean declarations**

- `DaggerOriginalSimplicialActionModelCategory.modelStructure`
- `DaggerOriginalSimplicialActionModelCategory.weakEquivalence_iff_underlying`
- `DaggerOriginalSimplicialActionModelCategory.fibration_iff_underlying`

**Source files**

- `lean/OriginalSimplicialActionModelCategory.lean`: [line 126](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalSimplicialActionModelCategory.lean#L126), [line 58](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalSimplicialActionModelCategory.lean#L58), [line 131](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalSimplicialActionModelCategory.lean#L131).

**Construction and reuse**

The free-boundary and free-horn generators, finite-source smallness, and closure of weak equivalences are verified for this action category. The construction uses Mathlib, the ported TopPackage machinery, and the ordinary Kan model structure; it does not present that general machinery as a new theorem.

<a id="result-4-3"></a>

## Result 4.3

Title in the PDF: `The Borel model structure on topological $C_2$-actions`.

**Lean declarations**

- `DaggerOriginalBorelModelCategory.modelStructure`
- `DaggerOriginalBorelModelCategory.weakEquivalence_iff_underlying`
- `DaggerOriginalBorelModelCategory.fibration_iff_underlying`
- `DaggerOriginalBorelModelCategory.cofibration_iff_original`

**Source files**

- `lean/OriginalBorelModelCategory.lean`: [line 73](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalBorelModelCategory.lean#L73), [line 79](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalBorelModelCategory.lean#L79), [line 85](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalBorelModelCategory.lean#L85), [line 91](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalBorelModelCategory.lean#L91).

**Construction and reuse**

This is a concrete model construction for the action category, using free realized boundaries and horns and finite free realization sources. The underlying topological q-model and package machinery are reused from pinned TopCatModelCategory sources; their upstream proofs are not claimed as new independent proofs here.

<a id="result-4-4"></a>

## Result 4.4

Title in the PDF: `Cofibrancy of $E_{\bullet}C_2$ and contractibility of $EC_2$`.

**Lean declarations**

- `DaggerOriginalEC2SimplicialProjectiveCofibrancy.originalSimplicialEC2_isCofibrant`
- `DaggerOriginalEC2RealizationContractibility.realizedContractibleSpace`
- `DaggerOriginalEC2EquivariantRelativeCellComplex.equivariantRelativeCellComplex`

**Source files**

- `lean/OriginalEC2SimplicialProjectiveCofibrancy.lean`: [line 60](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalEC2SimplicialProjectiveCofibrancy.lean#L60).
- `lean/OriginalEC2RealizationContractibility.lean`: [line 58](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalEC2RealizationContractibility.lean#L58).
- `lean/OriginalEC2EquivariantRelativeCellComplex.lean`: [line 84](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/OriginalEC2EquivariantRelativeCellComplex.lean#L84).

**Construction and reuse**

The action, skeletal pushouts, equivariant relative cell complex, and simplicial contraction are constructed for the original $E_{\bullet}C_2$. General cell-complex and topological-realization APIs are reused from Mathlib and TopCat.

<a id="result-4-5"></a>

## Result 4.5

Title in the PDF: `Kan fibers of prefix mapping spaces`.

**Lean declarations**

- `DaggerActualQuasicategoryMappingFibres.prefixMapping_kan`
- `DaggerActualQuasicategoryMappingFibres.leftMapping_kan`

**Source files**

- `lean/ActualQuasicategoryMappingFibres.lean`: [line 32](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualQuasicategoryMappingFibres.lean#L32), [line 37](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualQuasicategoryMappingFibres.lean#L37).

**Construction and reuse**

The proof uses lifting for the original coslice projection and the Kan criterion for its fibers. The statement covers every prefix simplex and terminal vertex, rather than an individual simplicial face calculation.

<a id="result-4-6"></a>

## Result 4.6

Title in the PDF: `Weak-equivalence invariance of right mapping spaces`.

**Lean declarations**

- `DaggerActualRightMappingWeakInvariance.map_weak_of_categorical_weak`

**Source files**

- `lean/ActualRightMappingWeakInvariance.lean`: [line 36](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualRightMappingWeakInvariance.lean#L36).

**Construction and reuse**

The proof uses the original right-cone mapping spaces, a span for categorical weak equivalences, and lifting. It is distinct from the unitary-core criterion in the dagger Theorem C.

<a id="result-4-7"></a>

## Result 4.7

Title in the PDF: `Right-cone mapping spaces and $Q_{\mathrm{rc}}$-singular enriched Homs`.

**Lean declarations**

- `DaggerActualRightConeSingularComparisonIso.comparisonIso`
- `DaggerActualRightConeSingularComparisonIso.comparison_app_bijective`

**Source files**

- `lean/ActualRightConeSingularComparisonIso.lean`: [line 43](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualRightConeSingularComparisonIso.lean#L43), [line 17](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/ActualRightConeSingularComparisonIso.lean#L17).

**Construction and reuse**

The isomorphism compares the original cone evaluation with the original $Q_{\mathrm{rc}}$-singular construction. It concerns mapping objects and is separate from the ordinary rigidification--coherent-nerve adjunction itself.

<a id="reused-foundations"></a>

## Reused foundations

The ordinary Kan--Quillen model structure and the boundary lifting criterion
are reused from the pinned compatibility port of Joël Riou's
[TopCatModelCategory](https://github.com/joelriou/topcat-model-category/tree/6c0c356fea469689fe76baeb47ba773460dfacee).
They are credited as upstream proofs, not new independent proofs in this project.

- `SSet.modelCategoryQuillen.weakEquivalence_iff_of_fibration`
- `SSet.modelCategoryQuillen.rlp_I_eq_trivialFibrations`
- `SSet.modelCategoryQuillen.inst`

- [KeyLemma.lean](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/TopCatModelCategory/SSet/KeyLemma.lean#L150)
- [ModelCategorySSet.lean](https://github.com/Yonoha/dagger-models-lean-part-i/blob/9ee62295a79ef61269259e27216afc0292458931/lean/TopCatModelCategory/ModelCategorySSet.lean#L20)
