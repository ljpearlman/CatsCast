To create a new episode wordcloud:
1. Save the episode as utf-8 text. If it's a Word file, make sure no formatting is showing, then save as text and select utf-8 for encoding and CR+LF for line separators.
2. Remove any extranneous header info from the text file.
3. Run wcloud: python wcloud.py -m cat.jpg -o <episode_dir>/wordcloud.jpg <episode_dir>/<text_file>
4. Look at the wordcloud.jpg file. If you want to tweak the results, you can also include words in a stop file and specify that with the -s flag
5. The worldcloud image will have the cat silhouette with words inside on a black background, with a thick white outline of the silhouette. Open the image in an image editor (like Photoshop or Pixelmator) and turn everything outside of the silhouette white. The outline is the only white in the image, so you can do a "magic selection" in any spot outside of the silhouette, and then click on the paint can (in Pixelmator) to fill the whole area.
6. Save the image as a jpeg, and you're done! Don't forget to specify alt text if you post it anywhere.
