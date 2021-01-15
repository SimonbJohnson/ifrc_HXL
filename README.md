# HXL Data from IFRC GO

IFRC GO data to download in HXL format. For each download there can be up to 4 links:

|Link type|Purpose|
|:--------|:------|
|**CSV**| CSV link for use in spreadsheets and other applications |
|**Edit recipe** | A link to the the HXL Proxy editor where you can adjust the recipe. This could be for filtering the data to a specific year or region |
|**Launch HXL Dash**| A link to the data preloaded into HXLDash. HXLDash is a fast way to generate and share charts and maps of the data. This visualition will be auto updating to match IFRCO GO data |
|**HXL Dash Example**| An example dashboard created with this data set. |

All links are auto updating to the latest data.

## Appeals and DREFs
HXL links for Appeals and DREF data

| Data Name                    | Excel Download | Link to modify this file| Launch HXLDash |HXLDash Example
|----------------------------|----------------|-------------------------|-------------------------|------------|
| All active Appeals and DREFs | [CSV](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=cut&cut-skip-untagged01=on&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-05-header=atype_display&tagger-05-tag=%23meta%2Bappeal%2Btype&tagger-06-header=code&tagger-06-tag=%23meta%2Bappeal%2Bid&tagger-11-header=country.iso&tagger-11-tag=%23country%2Bcode%2Bv_iso2&tagger-12-header=country.iso3&tagger-12-tag=%23country%2Bcode%2Bv_iso3&tagger-13-header=country.name&tagger-13-tag=%23country%2Bname&tagger-17-header=country.society_name&tagger-17-tag=%23org%2Bnational_society&tagger-19-header=dtype.id&tagger-19-tag=%23cause%2Bid&tagger-20-header=dtype.name&tagger-20-tag=%23cause%2Bname&tagger-22-header=end_date&tagger-22-tag=%23date%2Bend&tagger-26-header=name&tagger-26-tag=%23crisis%2Bname&tagger-28-header=num_beneficiaries&tagger-28-tag=%23beneficiaries%2Bnum&tagger-29-header=region.id&tagger-29-tag=%23region%2Bid&tagger-31-header=region.name&tagger-31-tag=%23region%2Bname&tagger-33-header=sector&tagger-33-tag=%23region%2Bname%2Boffice&tagger-34-header=start_date&tagger-34-tag=%23date%2Bstart&tagger-35-header=status&tagger-35-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26status%3D0) | [Edit Recipe](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Launch](https://hxldash.com/create/https%3A%2F%2Fproxy.hxlstandard.org%2Fdata.csv%3Fdest%3Ddata_edit%26filter01%3Dselect%26filter-label01%3DFilter%2Bfor%2Bonly%2Bactive%2Bappeals%2Band%2Bdrefs%26select-query01-01%3D%2B%2523status%2B%253D%2BActive%26filter02%3Dcut%26filter-label02%3DRemove%2Bcolumns%2Bwithout%2BHXL%2Btags%26cut-skip-untagged02%3Don%26tagger-match-all%3Don%26tagger-01-header%3Daid%26tagger-01-tag%3D%2523meta%252Bid%26tagger-02-header%3Damount_funded%26tagger-02-tag%3D%2523value%252Bfunded%26tagger-03-header%3Damount_requested%26tagger-03-tag%3D%2523value%252Brequested%26tagger-04-header%3Datype%26tagger-04-tag%3D%2523meta%252Bappeal%252Btype%26tagger-05-header%3Dcode%26tagger-05-tag%3D%2523meta%252Bappeal%252Bid%26tagger-08-header%3Dcountry.iso%26tagger-08-tag%3D%2523country%252Bcode%26tagger-09-header%3Dcountry.name%26tagger-09-tag%3D%2523country%252Bname%26tagger-11-header%3Dcountry.society_name%26tagger-11-tag%3D%2523org%252Bnational_society%26tagger-13-header%3Ddtype.id%26tagger-13-tag%3D%2523cause%252Bid%26tagger-14-header%3Ddtype.name%26tagger-14-tag%3D%2523cause%252Bname%26tagger-16-header%3Dend_date%26tagger-16-tag%3D%2523date%252Bend%26tagger-20-header%3Dname%26tagger-20-tag%3D%2523crisis%252Bname%26tagger-22-header%3Dnum_beneficiaries%26tagger-22-tag%3D%2523beneficiaries%252Bnum%26tagger-23-header%3Dregion.id%26tagger-23-tag%3D%2523region%252Bid%26tagger-24-header%3Dregion.name%26tagger-24-tag%3D%2523region%252Bname%26tagger-26-header%3Dsector%26tagger-26-tag%3D%2523region%252Bname%252Boffice%26tagger-27-header%3Dstart_date%26tagger-27-tag%3D%2523date%252Bstart%26tagger-28-header%3Dstatus%26tagger-28-tag%3D%2523status%26header-row%3D1%26url%3Dhttps%253A%252F%252Fgoadmin.ifrc.org%252Fapi%252Fv2%252Fappeal%252F%253Fformat%253Dcsv%2526limit%253D500)|[Example](https://hxldash.com/view/327)	| All active Appeals and DREFs | [CSV](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=cut&cut-skip-untagged01=on&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-05-header=atype_display&tagger-05-tag=%23meta%2Bappeal%2Btype&tagger-06-header=code&tagger-06-tag=%23meta%2Bappeal%2Bid&tagger-11-header=country.iso&tagger-11-tag=%23country%2Bcode%2Bv_iso2&tagger-12-header=country.iso3&tagger-12-tag=%23country%2Bcode%2Bv_iso3&tagger-13-header=country.name&tagger-13-tag=%23country%2Bname&tagger-17-header=country.society_name&tagger-17-tag=%23org%2Bnational_society&tagger-19-header=dtype.id&tagger-19-tag=%23cause%2Bid&tagger-20-header=dtype.name&tagger-20-tag=%23cause%2Bname&tagger-22-header=end_date&tagger-22-tag=%23date%2Bend&tagger-26-header=name&tagger-26-tag=%23crisis%2Bname&tagger-28-header=num_beneficiaries&tagger-28-tag=%23beneficiaries%2Bnum&tagger-29-header=region.id&tagger-29-tag=%23region%2Bid&tagger-31-header=region.name&tagger-31-tag=%23region%2Bname&tagger-33-header=sector&tagger-33-tag=%23region%2Bname%2Boffice&tagger-34-header=start_date&tagger-34-tag=%23date%2Bstart&tagger-35-header=status&tagger-35-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26status%3D0)||
| All active Appeals | [CSV](https://proxy.hxlstandard.org/data.csv?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&select-query03-01=%23meta%2Bappeal%2Btype+%3D+appeal&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Edit Recipe](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&select-query03-01=%23meta%2Bappeal%2Btype+%3D+appeal&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Launch](https://hxldash.com/create/https%3A%2F%2Fproxy.hxlstandard.org%2Fdata.csv%3Fdest%3Ddata_edit%26filter01%3Dselect%26filter-label01%3DFilter%2Bfor%2Bonly%2Bactive%2Bappeals%2Band%2Bdrefs%26select-query01-01%3D%2B%2523status%2B%253D%2BActive%26filter02%3Dcut%26filter-label02%3DRemove%2Bcolumns%2Bwithout%2BHXL%2Btags%26cut-skip-untagged02%3Don%26filter03%3Dselect%26select-query03-01%3D%2523meta%252Bappeal%252Btype%2B%253D%2Bappeal%26tagger-match-all%3Don%26tagger-01-header%3Daid%26tagger-01-tag%3D%2523meta%252Bid%26tagger-02-header%3Damount_funded%26tagger-02-tag%3D%2523value%252Bfunded%26tagger-03-header%3Damount_requested%26tagger-03-tag%3D%2523value%252Brequested%26tagger-04-header%3Datype%26tagger-04-tag%3D%2523meta%252Bappeal%252Btype%26tagger-05-header%3Dcode%26tagger-05-tag%3D%2523meta%252Bappeal%252Bid%26tagger-08-header%3Dcountry.iso%26tagger-08-tag%3D%2523country%252Bcode%26tagger-09-header%3Dcountry.name%26tagger-09-tag%3D%2523country%252Bname%26tagger-11-header%3Dcountry.society_name%26tagger-11-tag%3D%2523org%252Bnational_society%26tagger-13-header%3Ddtype.id%26tagger-13-tag%3D%2523cause%252Bid%26tagger-14-header%3Ddtype.name%26tagger-14-tag%3D%2523cause%252Bname%26tagger-16-header%3Dend_date%26tagger-16-tag%3D%2523date%252Bend%26tagger-20-header%3Dname%26tagger-20-tag%3D%2523crisis%252Bname%26tagger-22-header%3Dnum_beneficiaries%26tagger-22-tag%3D%2523beneficiaries%252Bnum%26tagger-23-header%3Dregion.id%26tagger-23-tag%3D%2523region%252Bid%26tagger-24-header%3Dregion.name%26tagger-24-tag%3D%2523region%252Bname%26tagger-26-header%3Dsector%26tagger-26-tag%3D%2523region%252Bname%252Boffice%26tagger-27-header%3Dstart_date%26tagger-27-tag%3D%2523date%252Bstart%26tagger-28-header%3Dstatus%26tagger-28-tag%3D%2523status%26header-row%3D1%26url%3Dhttps%253A%252F%252Fgoadmin.ifrc.org%252Fapi%252Fv2%252Fappeal%252F%253Fformat%253Dcsv%2526limit%253D500)||
| All active DREFs | [CSV](https://proxy.hxlstandard.org/data.csv?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&select-query03-01=%23meta%2Bappeal%2Btype+%3D+Dref&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Edit Recipe](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&select-query03-01=%23meta%2Bappeal%2Btype+%3D+Dref&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Launch](https://hxldash.com/create/https%3A%2F%2Fproxy.hxlstandard.org%2Fdata.csv%3Fdest%3Ddata_edit%26filter01%3Dselect%26filter-label01%3DFilter%2Bfor%2Bonly%2Bactive%2Bappeals%2Band%2Bdrefs%26select-query01-01%3D%2B%2523status%2B%253D%2BActive%26filter02%3Dcut%26filter-label02%3DRemove%2Bcolumns%2Bwithout%2BHXL%2Btags%26cut-skip-untagged02%3Don%26filter03%3Dselect%26select-query03-01%3D%2523meta%252Bappeal%252Btype%2B%253D%2BDref%26tagger-match-all%3Don%26tagger-01-header%3Daid%26tagger-01-tag%3D%2523meta%252Bid%26tagger-02-header%3Damount_funded%26tagger-02-tag%3D%2523value%252Bfunded%26tagger-03-header%3Damount_requested%26tagger-03-tag%3D%2523value%252Brequested%26tagger-04-header%3Datype%26tagger-04-tag%3D%2523meta%252Bappeal%252Btype%26tagger-05-header%3Dcode%26tagger-05-tag%3D%2523meta%252Bappeal%252Bid%26tagger-08-header%3Dcountry.iso%26tagger-08-tag%3D%2523country%252Bcode%26tagger-09-header%3Dcountry.name%26tagger-09-tag%3D%2523country%252Bname%26tagger-11-header%3Dcountry.society_name%26tagger-11-tag%3D%2523org%252Bnational_society%26tagger-13-header%3Ddtype.id%26tagger-13-tag%3D%2523cause%252Bid%26tagger-14-header%3Ddtype.name%26tagger-14-tag%3D%2523cause%252Bname%26tagger-16-header%3Dend_date%26tagger-16-tag%3D%2523date%252Bend%26tagger-20-header%3Dname%26tagger-20-tag%3D%2523crisis%252Bname%26tagger-22-header%3Dnum_beneficiaries%26tagger-22-tag%3D%2523beneficiaries%252Bnum%26tagger-23-header%3Dregion.id%26tagger-23-tag%3D%2523region%252Bid%26tagger-24-header%3Dregion.name%26tagger-24-tag%3D%2523region%252Bname%26tagger-26-header%3Dsector%26tagger-26-tag%3D%2523region%252Bname%252Boffice%26tagger-27-header%3Dstart_date%26tagger-27-tag%3D%2523date%252Bstart%26tagger-28-header%3Dstatus%26tagger-28-tag%3D%2523status%26header-row%3D1%26url%3Dhttps%253A%252F%252Fgoadmin.ifrc.org%252Fapi%252Fv2%252Fappeal%252F%253Fformat%253Dcsv%2526limit%253D500)|
|All historical Appeals and DREFs|[CSV](https://proxy.hxlstandard.org/data.csv?dest=data_edit&filter01=cut&filter-label01=Remove+columns+without+HXL+tags&cut-skip-untagged01=on&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D50000) (Slow) |[Edit recipe](https://proxy.hxlstandard.org/data?dest=data_edit&filter01=cut&filter-label01=Remove+columns+without+HXL+tags&cut-skip-untagged01=on&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D50000) (Slow)| Not Available |||


## Example filtered Appeals and DREFs

Use the example HXL recipes below to construct your own downloads by region, years, national societies and more. If you have not created a download recipe before then follow this 1 minute tutorial.

| Data Name                    | Excel Download | Link to modify this file|
|----------------------------|----------------|-------------------------|
| Active Appeals and DREFs in Africa region | [CSV](https://proxy.hxlstandard.org/data.csv?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&filter-label03=Select+rows+just+for+Africa&select-query03-01=%23region%2Bname+%3D+Africa&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Edit Recipe](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=select&filter-label01=Filter+for+only+active+appeals+and+drefs&select-query01-01=+%23status+%3D+Active&filter02=cut&filter-label02=Remove+columns+without+HXL+tags&cut-skip-untagged02=on&filter03=select&filter-label03=Select+rows+just+for+Africa&select-query03-01=%23region%2Bname+%3D+Africa&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) |
| Appeals launched in 2020 | [CSV](https://proxy.hxlstandard.org/data.csv?dest=data_edit&filter01=cut&filter-label01=Remove+columns+without+HXL+tags&cut-skip-untagged01=on&filter02=select&filter-label02=Filter+for+only+active+appeals+and+drefs&select-query02-01=+%23status+%3D+Active&filter03=select&filter-label03=Select+only+appeals&select-query03-01=%23meta%2Bappeal%2Btype+%3D+appeal&filter04=select&filter-label04=Filter+for+appeals+starting+after+2019-12-31&select-query04-01=%23date%2Bstart%3E2019-12-31&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) | [Edit Recipe](https://proxy.hxlstandard.org/data/edit?dest=data_edit&filter01=cut&filter-label01=Remove+columns+without+HXL+tags&cut-skip-untagged01=on&filter02=select&filter-label02=Filter+for+only+active+appeals+and+drefs&select-query02-01=+%23status+%3D+Active&filter03=select&filter-label03=Select+only+appeals&select-query03-01=%23meta%2Bappeal%2Btype+%3D+appeal&filter04=select&filter-label04=Filter+for+appeals+starting+after+2019-12-31&select-query04-01=%23date%2Bstart%3E2019-12-31&tagger-match-all=on&tagger-01-header=aid&tagger-01-tag=%23meta%2Bid&tagger-02-header=amount_funded&tagger-02-tag=%23value%2Bfunded&tagger-03-header=amount_requested&tagger-03-tag=%23value%2Brequested&tagger-04-header=atype&tagger-04-tag=%23meta%2Bappeal%2Btype&tagger-05-header=code&tagger-05-tag=%23meta%2Bappeal%2Bid&tagger-08-header=country.iso&tagger-08-tag=%23country%2Bcode&tagger-09-header=country.name&tagger-09-tag=%23country%2Bname&tagger-11-header=country.society_name&tagger-11-tag=%23org%2Bnational_society&tagger-13-header=dtype.id&tagger-13-tag=%23cause%2Bid&tagger-14-header=dtype.name&tagger-14-tag=%23cause%2Bname&tagger-16-header=end_date&tagger-16-tag=%23date%2Bend&tagger-20-header=name&tagger-20-tag=%23crisis%2Bname&tagger-22-header=num_beneficiaries&tagger-22-tag=%23beneficiaries%2Bnum&tagger-23-header=region.id&tagger-23-tag=%23region%2Bid&tagger-24-header=region.name&tagger-24-tag=%23region%2Bname&tagger-26-header=sector&tagger-26-tag=%23region%2Bname%2Boffice&tagger-27-header=start_date&tagger-27-tag=%23date%2Bstart&tagger-28-header=status&tagger-28-tag=%23status&header-row=1&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fappeal%2F%3Fformat%3Dcsv%26limit%3D500) |

## 3W (Who, What, Where)
| Data Name                    | Excel Download | Link to modify this file|
| ---------------------------- |----------------|-------------------------|
| All 3W records |[CSV](https://proxy.hxlstandard.org/data.csv?tagger-match-all=on&tagger-01-header=budget_amount&tagger-01-tag=%23value%2Bbudget&tagger-03-header=end_date&tagger-03-tag=%23date%2Bend&tagger-07-header=modified_at&tagger-07-tag=%23date%2Bupdate&tagger-08-header=name&tagger-08-tag=%23activity%2Bname&tagger-10-header=operation_type_display&tagger-10-tag=%23operations%2Btype&tagger-12-header=primary_sector_display&tagger-12-tag=%23sector&tagger-14-header=programme_type_display&tagger-14-tag=%23operations%2Btype2&tagger-17-header=project_country_detail.iso&tagger-17-tag=%23country%2Bcode&tagger-18-header=project_country_detail.name&tagger-18-tag=%23country%2Bname&tagger-20-header=project_country_detail.society_name&tagger-20-tag=%23org%2Bimplementor&tagger-29-header=reached_female&tagger-29-tag=%23reached%2Bf&tagger-30-header=reached_male&tagger-30-tag=%23reached%2Bm&tagger-31-header=reached_other&tagger-31-tag=%23reached%2Bo&tagger-32-header=reached_total&tagger-32-tag=%23reached%2Btotal&tagger-40-header=reporting_ns_detail.society_name&tagger-40-tag=%23org%2Bpartner&tagger-49-header=start_date&tagger-49-tag=%23date%2Bstart&tagger-51-header=status_display&tagger-51-tag=%23status&tagger-52-header=target_female&tagger-52-tag=%23target%2Bf&tagger-53-header=target_male&tagger-53-tag=%23target%2Bm&tagger-54-header=target_other&tagger-54-tag=%23target%2Bo&tagger-55-header=target_total&tagger-55-tag=%23target_total&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fproject%2F%3Fformat%3Dcsv&header-row=1&dest=data_view)|[Edit recipe](https://proxy.hxlstandard.org/data/edit?tagger-match-all=on&tagger-01-header=budget_amount&tagger-01-tag=%23value%2Bbudget&tagger-03-header=end_date&tagger-03-tag=%23date%2Bend&tagger-07-header=modified_at&tagger-07-tag=%23date%2Bupdate&tagger-08-header=name&tagger-08-tag=%23activity%2Bname&tagger-10-header=operation_type_display&tagger-10-tag=%23operations%2Btype&tagger-12-header=primary_sector_display&tagger-12-tag=%23sector&tagger-14-header=programme_type_display&tagger-14-tag=%23operations%2Btype2&tagger-17-header=project_country_detail.iso&tagger-17-tag=%23country%2Bcode&tagger-18-header=project_country_detail.name&tagger-18-tag=%23country%2Bname&tagger-20-header=project_country_detail.society_name&tagger-20-tag=%23org%2Bimplementor&tagger-29-header=reached_female&tagger-29-tag=%23reached%2Bf&tagger-30-header=reached_male&tagger-30-tag=%23reached%2Bm&tagger-31-header=reached_other&tagger-31-tag=%23reached%2Bo&tagger-32-header=reached_total&tagger-32-tag=%23reached%2Btotal&tagger-40-header=reporting_ns_detail.society_name&tagger-40-tag=%23org%2Bpartner&tagger-49-header=start_date&tagger-49-tag=%23date%2Bstart&tagger-51-header=status_display&tagger-51-tag=%23status&tagger-52-header=target_female&tagger-52-tag=%23target%2Bf&tagger-53-header=target_male&tagger-53-tag=%23target%2Bm&tagger-54-header=target_other&tagger-54-tag=%23target%2Bo&tagger-55-header=target_total&tagger-55-tag=%23target_total&url=https%3A%2F%2Fgoadmin.ifrc.org%2Fapi%2Fv2%2Fproject%2F%3Fformat%3Dcsv&header-row=1&dest=data_view)|
