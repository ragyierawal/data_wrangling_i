Tidy Data
================
Ragyie Rawal

## pivot longer

Load the PULSE data

``` r
pulse_df = 
  read_sas("data_import_examples/public_pulse_data.sas7bdat") %>% 
  janitor::clean_names()
```
