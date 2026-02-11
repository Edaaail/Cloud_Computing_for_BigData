PRD: BCC LegalGuardian AI
1. JOB TO BE DONE

When I receive a non-standard vendor contract with tight business deadlines and high regulatory stakes, I want to automatically identify and compare high-risk clauses against Kazakhstan’s specific legal requirements and BCC’s risk appetite, so I can provide an accurate, high-speed legal opinion that prevents financial loss and regulatory violations without being the project bottleneck.

2. USER PERSONA

Marat, Senior Legal Counsel at Bank CenterCredit.
Marat is a highly experienced, risk-averse legal professional. He is skeptical of generic "Legal Tech" because he has been burned by tools that miss nuances. He values accuracy over automation and carries the heavy burden of being the "final safeguard" for the bank’s institutional safety.

3. PROBLEM STATEMENT

The current manual review process for IT procurement is slow and high-risk because vendors use diverse templates that "hide" liability caps and non-compliant data clauses. Furthermore, the lack of a digital gate allows Business teams to bypass Legal, leaving Marat to "rubber stamp" risky agreements after verbal commitments are already made.

4. FUNCTIONAL REQUIREMENTS
4.1 Kazakhstan-Specific Regulatory Intelligence

KZ Compliance Mapping: The AI must detect and flag clauses specifically related to the Agency for Regulation and Development of the Financial Market (ARDFM) requirements, including Banking Secrecy and the Law on Personal Data.

Contextual Intent Analysis: Rather than simple keyword matching (e.g., "Liability"), the AI must identify "Risk Shifting" language even when hidden under misleading headers like "General Terms," "Miscellaneous," or "Indemnification."

Data Residency Verification: Automatically flag any clause that suggests cross-border data transfer or storage that contradicts Kazakhstan's data residency requirements.

4.2 Comparative Risk Benchmarking

Deviation Analysis: The AI must compare the vendor's PDF text against BCC’s internal "Gold Standard" templates for IT procurement and BCC-HUB agreements.

Liability Cap Detection: The agent must extract specific numerical values for liability (e.g., 10% of contract value, 12-month fee cap) and flag them if they fall below BCC’s mandatory risk thresholds.

Termination Right Audit: Identify "asymmetric" termination clauses where the vendor has more rights to end the contract than the bank.

4.3 Intelligent Document Processing (IDP)

High-Fidelity OCR: The AI must process "messy" documents, including poorly scanned PDFs or documents with handwritten notes, to ensure no "hidden" annexes are missed.

Automated Feedback Generation: The AI must generate draft "Legal Comments" in a format that Marat can copy-paste directly into an email or a document management system, citing exactly which BCC policy or KZ law is being challenged.

5. USER EXPERIENCE REQUIREMENTS

"Explainable AI" Interface: Every flagged risk must include a "Reasoning" tooltip. It should say: "I flagged this because Article 18 of the Banking Secrecy law requires X, but this clause says Y." (To build Marat's trust).

Side-by-Side Comparison: A split-screen view showing the Vendor's PDF on the left and the AI’s risk extraction/BCC’s preferred clause on the right.

Zero-Admin Workflow: The tool must not require Marat to fill out extra metadata fields. The review should start simply by uploading a file.

6. SUCCESS METRICS

Review Velocity: Reduction in the average time taken to complete a first-pass review of a 40+ page vendor agreement (Target: From 4 hours to 30 minutes).

Critical Risk Catch-Rate: A "Zero Miss" rate on 10% liability caps and data residency violations in test sets compared to manual historical reviews.

Internal Throughput: Percentage of IT procurement contracts reviewed before Business signature, facilitated by the increased speed of the Legal department.

7. NON-FUNCTIONAL REQUIREMENTS

Data Sovereignty: The AI model and all processed contract data must reside on-premise or within a secured KZ-based cloud environment to satisfy Banking Secrecy laws.

Language Support: Full support for Russian and English (the primary languages for vendor IT contracts in BCC).

Audit Trail: Maintain a permanent log of what the AI flagged and what Marat edited/overrode for Internal Audit and Board reporting.

CONSTRAINTS

Human-in-the-loop: The system will never have "Auto-Approve" functionality. It generates a "Risk Report" for Marat to sign off on.

No Replacement: The tool is marketed as a "Junior Associate" that does the reading, while Marat remains the "Partner" who does the thinking.
