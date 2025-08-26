# WormNotebooks
Here you will find notebooks that demonstrate the usage of computational tools on _C. elegans_ data. The notebooks can be used on Google Colab without any lokal installation.

## SAM-2 for segmentation and tracking of worms in videos
The [segment_worm_video_with_sam2](https://github.com/pwetterauer/WormNotebooks/blob/dev/segment_worm_video_with_sam2.ipynb) notebook uses the Segment Anything Model 2 (SAM 2) from Meta AI. It is a modified version of the video segmentation example notebook in the [sam-2 repository](https://github.com/facebookresearch/sam2). Multiple worms are segmented in one frame guided by point prompts. Then the masks are propagated to all frames in the video. The results (masks for every worm in each frame) can be saved as pickle-file.

![sam-2 workflow](https://github.com/pwetterauer/WormNotebooks/blob/dev/ilg5_sam2_workflow.png)
