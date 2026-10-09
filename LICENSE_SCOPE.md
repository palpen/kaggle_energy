# License scope

The root [MIT License](LICENSE), copyright (c) 2026 Palermo Penano, applies only to the original work identified below that is owned by Palermo Penano. In that license, "Software" means these original contributions, not every item stored in this repository.

## Covered original work

- Palermo Penano's original data-preparation and orchestration code in main/make_small_dataset.py, main/tsoutliers/prepare_data.R, and main/tsoutliers/remove_outliers.py.
- Palermo's original experiment code and commentary in main/main_palermo.ipynb and the original df_sample_random_buildings, print_full, and rolling_stat helpers in main/utils.py.

## Exclusions and retained rights

- main/simple_halfhalf.py is explicitly ported from Rohan Rao's ASHRAE half-and-half Kaggle notebook; the upstream expression is not covered by Palermo's MIT grant.
- reduce_mem_usage in main/utils.py credits gemartin's Kaggle notebook. add_datepart is derived from fastai; its upstream Apache-2.0 license is retained separately.
- main/tsoutliers/tsoutliers.R derives from a Stack Exchange answer. Copied snippets or attributed Kaggle examples in notebooks, and any external competition data or notebook output reproducing that data, are excluded.

Kaggle and Stack Exchange source-specific grants/notices have not been verified; excluded from the new MIT grant. fastai's Apache-2.0 terms are verified.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for attribution and any separately retained license texts. All existing copyright, attribution, and license notices remain in effect. This scope statement identifies the material offered under MIT; it does not change the standard MIT terms for the covered original work or grant rights held by someone else.
