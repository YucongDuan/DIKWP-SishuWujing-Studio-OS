# DIKWP SishuWujing Studio OS

DIKWP SishuWujing Studio OS is an offline-first learning, teaching, and research system for the Four Books and Five Classics. It turns classical passages into DIKWP concept ledgers, student study plans, teacher lesson packs, misconception maps, theory development matrices, and AI-use boundaries.

## Quick Start

```bash
pip install -e .
sishuwujing analyze examples/sample_classics_learning_case.json --out outputs/demo
sishuwujing guard "把论语用于要求学生绝对服从"
sishuwujing static-audit src --out outputs/demo/static_boundary_audit_report.json
```

Open `index.html` for the standalone browser demo.

## Boundary

The system is for classical learning, teaching, translation integrity, and modern ethical reflection. It must not be used to justify coercion, discrimination, humiliation, violence, legal replacement, or fabricated classical authority.

## Attribution

DIKWP framework attribution: Yucong Duan / DIKWP. See `NOTICE` and `CITATION.cff`.
