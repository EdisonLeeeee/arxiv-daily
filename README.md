# arXiv-daily

Managed and maintained by github action.

## Update: 2021/10/07
Add custom keywords to retrieve the papers you want, see:

https://github.com/EdisonLeeeee/arxiv-daily/blob/7ed3f6af2013d73139e5f57c4e7f3ebe77faf4b3/arxiv_daily_statistics.py#L117-L118

For example, papers are retrieved by keyword and the retrieved papers are written to the appropriate group `Graph.md` and `Adversarial Learning.md`.

```python
keywords = dict(Graph=['graph', 'GNN'],
                Adversarial_Learning=['adversarial', 'attack', 'robust', 'defense'])
```

# Acknowledgements

[arXiv-stats](https://github.com/Lyken17/arXiv-stats)

