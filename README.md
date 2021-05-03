# Title



sklearn.linear_model.LogisticRegression¶
# kowaza 小技

> Little tips & tricks for machine learning and AI development.

kowazaに大したものは含まれていません。pipパッケージを公開してみたいのと、プロジェクト間でコピペの手間を減らすためにちょっとしたツールやヒントをより集めました。

## インストール

`pip install kowaza`

## 開発環境

Install packages

    mamba env update -f kowaza-conda.yml -n kowaza
    conda activate kowaza
    python -m ipykernel install --user --name=kowaza
    jupyter labextension install jupyterlab-plotly
    pip install .
