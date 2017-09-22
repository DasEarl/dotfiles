# Fix Tearing
echo 'nvidia-settings --assign CurrentMetaMode="nvidia-auto-select +0+0 { ForceFullCompositionPipeline = On  }"' > /etc/profile.d/nvidia.sh
