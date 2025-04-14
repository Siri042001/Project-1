# update_status.py

from datetime import datetime

README_PATH = "README.md"

with open(README_PATH, "a") as f:
    f.write(f"\n\n_Last updated on {datetime.utcnow().strftime('%Y-%m-%d %H:%M:%S')} UTC_")
