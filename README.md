# ASN Bank export to YNAB usable CSV converter

Based on the Rabobank script by @EddoKloosterman I've made some changes so it works with ASN bank exports as well.

### Usage

1. Create an export from your bank account on the ASN website. Make sure you tick the box 'CSV met IBAN'.
![Screenshot of ASN Bank export view](http://cl.ly/1z1Q3u1o3S1j/Screen%20Shot%202015-12-09%20at%2019.40.23.png)
2. Download the script to your machine and run from terminal:
```php YnabCsvConverterASN.php ~/Downloads/yourASNexport.csv```
3. The script will create a new .csv file on your Desktop.
4. Import that file in YNAB.

