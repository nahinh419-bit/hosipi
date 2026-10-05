# HospiHelp

Advanced Flask starter website based on the supplied HospiHelp hand-drawn design.

## Features
- Home page
- Division / District / Area selectors
- Symptom checker
- Specialist recommendation
- Nearby hospital page
- Doctor profile
- Appointment booking
- My appointments
- Blood Finder from the 3-dot menu
- Responsive modern UI

## Run

```bash
pip install -r requirements.txt
python app.py
```

Open:

http://127.0.0.1:5000/

## Next database step
The demo currently uses Python lists so the UI works immediately.
You can later connect MySQL and replace DOCTORS/HOSPITALS with database queries.


## Accounts & persistent data
- Sign Up creates a real account in `hospihelp.db`.
- Email addresses must be unique.
- Passwords are stored as secure password hashes, not plain text.
- Login remains active during the browser session.
- Appointments are saved per user in the same SQLite database.
- `hospihelp.db` is created automatically the first time `python app.py` runs.
