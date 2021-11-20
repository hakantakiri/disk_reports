# S.M.A.R.T ctl usage
Using a SATA2USB interface `-d sat` is needed to use the vendor independent SAT standard
```
sudo smartctl -d sat -a <drive_name>
```

when not using a SATA2USB enclosure then `-d sat` can be avoided.
```
sudo smartctl -a <drive_name>
```
