LIBOL is an open-source library for large-scale online classification, which consists of a large family of efficient and scalable state-of-the-art online learning algorithms for solving both binary and multiclass online classification tasks. We have offered easy-to-use command-line tools and examples for users and developers, and also made documents available for both beginners and advanced users. LIBOL is not only a machine learning tool, but also a comprehensive experimental platform for online learning research.

The current version (V0.3.0) of LIBOL supports a total of 16 algorithms and variants for binary classification tasks, and a total of 13 algorithms and variants for multiclass classification tasks.

In general, the existing online learning algorithms for linear classification tasks can be grouped into two major categories: (i) first order learning (Rosenblatt, 1958; Crammer et al., 2006), and (ii) second order learning (Dredze et al., 2008; Wang et al., 2012; Yang et al., 2009). Example online learning algorithms in the first order learning category implemented in this library include:

> • Perceptron: the classical online learning algorithm (Rosenblatt, 1958);

> • ALMA: A New Approximate Maximal Margin Classification Algorithm (Gentile, 2001);

> • ROMMA: the relaxed online maxiumu margin algorithms (Li and Long, 2002);

> • OGD: the Online Gradient Descent (OGD) algorithms (Zinkevich, 2003);

> • PA: Passive Aggressive (PA) algorithms (Crammer et al., 2006);

Example algorithms in the second order online learning category implemented in this library include the following:

> • SOP: the Second Order Perceptron (SOP) algorithm (Cesa-Bianchi et al., 2005);

> • CW: the Confidence-Weighted (CW) learning algorithm (Dredze et al., 2008);

> • IELLIP: online learning algorithms by improved ellipsoid method (Yang et al., 2009);

> • AROW: the Adaptive Regularization of Weight Vectors (Crammer et al., 2009);

> • NAROW: New variant of Adaptive Regularization (Orabona and Crammer, 2010);

> • NHERD: the Normal Herding method via Gaussian Herding (Crammer and Lee, 2010)

> • SCW: the recently proposed Soft Confidence Weighted algorithms (Wang et al., 2012).

LIBOL is still being improved by improvements from practical users and new research results.

Scientific results produced using the software provided shall acknowledge
the use of LIBOL.
Please cite as

> Steven C.H. Hoi, Jialei Wang, and Peilin Zhao.
> LIBOL: A Library for Online Learning Algorithms.
> Nanyang Technological University, 2012.
> Software available at http://libol.stevenhoi.org/

More information can be found in our project website.