Singularity file for the recoll-webui.

Image building handled by singularity-hub.org

### Usage

```
singularity pull shub://photocyte/recoll-webui_singularity`
singularity exec --cleanenv recoll-webui_singularity_latest.sif /recollwebui/webui-standalone.py
```
