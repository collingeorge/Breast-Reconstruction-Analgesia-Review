# 2026.10-rc2 - educational review candidate

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Revised 27 October 2026 after the rc1 PRs were merged.

This pass corrects newly identified source and software defects and deliberately narrows unsupported clinical/methodological content. Earlier versions remain recoverable in Git history. See PUBLICATION_REVIEW.md for the precise scope and limitations, PROVENANCE.md for author statements, and RELEASE_MANIFEST.json for current-file hashes.

The candidate is not a clinical protocol, validated controller, systematic/scoping review certification, or legal opinion. No repository visibility change is included.

## Applied example set — 28 October 2026
Added 7 topic-specific male/female case pairs, a local copy of the shared anesthesia-options set, two levels of source mapping and an explicit verification standard. The profiles are entirely synthetic; the source checks are scoped and do not certify clinical validity. Existing clinical/manuscript text and PDF exports are preserved.


## 29 October 2026 — Portfolio presentation and reading path

Added a concise reader’s guide, explicit AI-assistance/authorship scope and review-status notes. Linked the portfolio home and corrected navigation wording. This presentation pass preserves substantive manuscripts, casebooks, code and existing exports. Repository visibility is unchanged.


## November 2026 — accuracy and governance review

Dated 5 November 2026. This is repository release 2026.11 (manuscript v8); the CITATION.cff version is now `2026.11`. The changes respond to an independent review of the manuscript and companion files.

- **PROSPECT hierarchy.** The manuscript, 02 and APPLIED_CASES now state the ranking in the 2020 PROSPECT guideline for major breast surgery. Paravertebral block was first choice (Grade A), PECS block was an alternative to PVB, and wound infiltration was an addition to a regional technique (Grade A); for lumpectomy-type procedures, infiltration was recommended. The files also state SAMBA's position (for mastectomy, PECS if PVB cannot be given, Strength A).
- **Current guidance cited in the body.** The 2026 PROSPECT update for major oncological breast surgery (Desai et al., Anaesthesia 2026, doi 10.1111/anae.70313) is now cited as current, and Jacobs et al. 2020 is labeled historical. Only the abstract and summaries of the update were reviewed. Other additions:
  - the 2026 ASA local and regional analgesia guideline (Anesthesiology 2026;144(1):19–43), cited under the ASA Task Force; individual authorship is not confirmed
  - the Fifth PONV consensus (Gan et al. 2025), with Gan 2020 labeled historical
  - the ASRA antithrombotic fifth edition (Kopp et al. 2025), with Horlocker 2018 labeled historical
- **Gabapentinoids.** The caveat from Verret et al. 2020 and Kharasch et al. 2020 now appears in Table 3 and Section 5.2 of the manuscript and in 02.
- **IV lidocaine.** The text now states the Foo et al. 2021 consensus position: no IV lidocaine during, or within the period of action of, other local-anesthetic interventions. The old cumulative-dose framing is gone.
- **References.** `06_References.md` gains entries 60–66 (ASA 2026, Desai 2026, Foo 2021, Gan 2025, Kharasch 2020, Kopp 2025, Verret 2020). Each per-document list is updated. The 27 October boilerplate footers were removed from all files, and their content was moved into the bodies. An unconfirmed PMID link (41237407) was removed.
- **Minor corrections:**
  - search re-run date corrected to 27 October 2026, and the archive filename corrected
  - abstract now says the documented strings failed on re-run and that the original search date was not recorded
  - exclusion criteria now name the cited letter, perspective and editorial exceptions
  - removed the unsourced claim that propofol TIVA is opioid-sparing, and reframed the Section 8.5 hypothesis
  - Paasche-Orlow denominator corrected (61 of 114 schools posted a standard)
  - "verified" changed to "identity-checked"
  - unsourced 02 Section 7 labeled as general background, and the ERAS/TIVA claim in 02 softened
  - wording fix on "pain" as a side effect
  - data-charting note flags figures not re-confirmed from abstracts
  - APPLIED_CASES gains an author/disclaimer line and a definition of Smart NOA
- **Governance.** Added HISTORICAL_VERSION_NOTICE.md and linked it from the README. Version labels are now consistent. The repository contains no PDF exports. The October 2026 notes above mention "PDF exports", but no PDF is present in this repository.
- **Not done.** The full texts of the 2025–2026 guidance documents were not reviewed. Owner re-checks of the extraction figures listed in manuscript Section 2.6 are still pending.
