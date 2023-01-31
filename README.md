# 42_piscine_rankings

## Installation and usage

```
pip3 install -r requirements.txt
```

After executing the command, add your **UID** and **secret key** in `config.yml`.

Then, all you have to do is using the following command :

```
python3 main.py
```

You will have to enter month, year and dates of the piscine. **Start date is included in the range, end date is not**. Therefore the end of a piscine have to be one day later than the real one.
The output will be a **CSV file** ordered by what you specified as an input.

*NB: This script can have some issues, please let me know if you find one!*
