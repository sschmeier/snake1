# Snakemake issue 1184 minimal example

https://bitbucket.org/snakemake/snakemake/issues/1184/

```bash
snakemake --version
5.4.5

snakemake -p --configfile config2.yaml
{'samples': 'samples2.tsv', 'contrasts': OrderedDict([('METS2-vs-PRIMARY2', ['METS2', 'PRIMARY2']), ('METS-vs-PRIMARY', ['METS', 'PRIMARY'])])}
```
