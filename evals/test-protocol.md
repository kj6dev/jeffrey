# Synthetic validation protocol

1. Use the actual work-approved model/runtime.
2. Load `runtime/behavior-instructions.md`.
3. Supply synthetic copies of the three state files.
4. Run all six scenarios plus closure/missing-context probes.
5. Capture the model's actual responses and model identity/settings when available.
6. Check hard gates first.
7. Fix failures by simplifying instructions or narrowing responsibility before adding machinery.
8. Re-run affected cases.
9. Only after hard failures are resolved should the three real state files be instantiated in the approved work environment.
10. Agree a maintenance ceiling before real use.

Do not treat author-written expected responses as the acceptance oracle. Evaluate actual behavior against the contract and scenario requirements.
