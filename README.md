# annotation-urls

URLs extracted from the [YouTube annotations archive](https://old.reddit.com/r/DataHoarder/comments/b7imx9/youtube_annotation_archive_annotation_data_from/).

This task was split into 4096 batches based on the first two characters of video ID. For each batch, 3 files are created: (1) containing a list of referenced video IDs, (2) containing a list of YouTube URLs, and (3) containing a list of external URLs. A file containing parsing exceptions across all batches (errors.txt) also exists. Code used for parsing is available at https://github.com/tech234a/annotation-extract/blob/main/main.py.
