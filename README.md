# Computer Tomography

Showing artificial tomographies of the file "Chest_ct.nii". Tomographies are perpendicular to the z-axis (3rd dimension) in angle steps of 30 degrees.

plot the 12 projections in the report and describe in detail how the projections where made

As an exercise, radon transforms and inverse radon transforms are implemented by hand (there exist multiple libraries for this functions though).

Radon transforms of slice 25 are transformed over 180 angles from 0-179 degrees.

Back-projection of the radon transform is implemented and the SSD error compared to the original slice computed.
Then, the process is repeated for a filtered back-projection.
