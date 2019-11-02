# Automatic-colorization

#Adjust render_factor (int) if image doesn't look quite right (max 64 on 11GB GPU).  The default here works for most photos.  
#It literally just is a number multiplied by 16 to get the square render resolution.  
#Note that this doesn't affect the resolution of the final output- the output is the same resolution as the input.
#Example:  render_factor=21 => color is rendered at 16x21 = 336x336 px

