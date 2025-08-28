### Container for tagged Audioserve dev builds

https://github.com/izderadicka/audioserve

Latest release

```bash
curl -s https://api.github.com/repos/izderadicka/audioserve/releases/latest | grep tag_name | cut -d '"' -f 4 | tr -d 'v'
```