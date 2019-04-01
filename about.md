---
layout: page
title: About
permalink: /about/
---

jblas is a fast linear algebra library for Java. jblas is based on BLAS and LAPACK, the de-facto industry standard for matrix computations, and uses state-of-the-art implementations like ATLAS for all its computational routines, making jBLAS very fast.

jblas can is essentially a light-wight wrapper around the BLAS and LAPACK routines. These packages have originated in the Fortran community which explains their often archaic API. On the other hand modern implementations are hard to beat performance wise. jblas aims to make this functionality available to Java programmers such that they do not have to worry about writing JNI interfaces and calling conventions of Fortran code.

jblas depends on an implementation of the LAPACK and BLAS routines. Currently it is tested with [ATLAS](http://math-atlas.sourceforge.net/) and [BLAS/LAPACK](http://www.netlib.org/lapack)
