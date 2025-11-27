# Sway Optimizations


| Sway tweaks                                          |                                                      							      |
|------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| shadows disable                        	       | Disables shadows			     	      							      |
| corner_radius 0				       | Makes corners more rounded	                      							      |
| blur disable	 				       | Disables blur					      							      |
| default_border pixel 1                               | Tiled windows get a 1-pixel border instead of the default thick CSD shadow thing			      |
| default_floating_border pixel 1 		       | Same for floating windows 										      |
| gaps inner 0 					       | No space between tiled windows 									      |
| gaps outer 0					       | No space between windows and screen edge 								      |
| AQ_NO_MODIFIERS=1                                    | Disables modifiers for DRM buffers.		      							      |
| RADV_PERFTEST=nggc,rt,sco		    	       | Enables Next Generation Geometry Culling,Rasterizer Toggle and Shader Cache Optimizations. 		      |