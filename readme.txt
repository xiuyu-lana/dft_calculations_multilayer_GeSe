
This project first start from constructing a structure file for GeSe-monolayer, then relax the unit cell to find the lattice parameters which result in lowest total energy. The next step is to compute the tensile modulus. We apply a series of deformations within the elastic region to the structure and calculate the regarding energies. After that, we keep increasing the deformations to find the maximum stress the material can bear.

The procedure above is repeated for bilayer, tri-layer, four-layer, etc. These calculations is also conducted on the bulk state of GeSe. We’re trying to find the point where the 2D material change to bulk material. As we increase the number of layers, there occurs a new factor we need to consider, that is, the manner of stacking. Different stacking manners are applied to these materials to see how the mechanical properties change.

All the calculations are conducted on High Performance Research Computing Clusters. VASP were used to do most calculations in this project. When relaxing the unit cell for optimal structure, the length in z-direction should be fixed because we don’t want to change the vacuum volume. The original version of VASP can’t execute such a job. Fortunately, Dr. Qian Xiaofeng has modified VASP to fix some lattice parameters when running the structure optimization job. Therefore, we are using the modified version of VASP in this project.



Reference:
 [1] Wang, H. and Qian, X., 2017. Giant optical second harmonic generation in two-dimensional multiferroics. Nano Letters, 17(8), pp.5027-5034.
 [2] Xu, Y., Zhang, H., Shao, H., Ni, G., Li, J., Lu, H., Zhang, R., Peng, B., Zhu, Y., Zhu, H. and Soukoulis,C.M., 2017. First-principles study on the electronic, optical, and transport properties of monolayer α-and β-GeSe. Physical Review B, 96(24), p.245421.
 [3] Wang, H., & Qian, X. (2017). Two-dimensional multiferroics in monolayer group IV monochalcogenides. 2D Materials, 4(1), 015042.
 [4] Wang, X., Jiang, X. F., Li, Z., Xue, Y., Wu, J., Wang, Y., ... & Xue, D. J. (2020). Identifying the Crystalline Orientation of Mechanically Exfoliated Anisotropic Layered Materials through Their Morphologies. Advanced Materials Interfaces, 2000612