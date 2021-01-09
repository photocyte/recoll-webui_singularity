Singularity file for the recoll-webui.

Image building handled by [singularity-hub.org](https://singularity-hub.org)

### Usage

```
singularity pull shub://photocyte/recoll-webui_singularity`
singularity exec --cleanenv recoll-webui_singularity_latest.sif /recollwebui/webui-standalone.py
## Then navigate to http://127.0.0.1:13337
## The .recoll directory in your home directory will need to be, or be symlinked to, a real recoll index directory, included a previous indexed xapiandb 
```
