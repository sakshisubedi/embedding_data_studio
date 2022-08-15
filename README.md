# embeding_data_studio

### Steps followed
- Uploaded [sample data](./sample_data.csv) in bigquery with project_name as `cfg-210814`, dataset_name as `Gene` and table_name as `clinical_data`.
![bigquery_ui](./assets/bigquery_ui.png)
- Connected data studio with the created bigquery table.
![data_studio_ui](./assets/data_studio_ui.png)
- The generated chart is then embedded into website. Deployed url is [embeding_data_studio](https://embedding-data-studio.netlify.app/).
The website displays scattered plot for each chrom type. The X-axis represent each `CHROM` type and Y-axis represent `AF_EXAC`. The chart additionally includes a drop down filter to either include or exclude the specific CHROM from the scatter plot.