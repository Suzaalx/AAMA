# Routing notes

Issues:
- LoginScreen sets district 'Pokhara Metro' for FCHV-1002 but findNearestPsychiatrist expects known districts
- DISTRICT_NEIGHBORS doesn't include Pokhara Metro
- Need stable identifiers, separate from translated names
- If no match/available, system must report condition clearly
