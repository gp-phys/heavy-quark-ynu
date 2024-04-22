These are hard coefficients related to arXiv: hep-ph/2402.05436, created by Mathematica 7. 

1) tree-level hard coefficients: 

tildeD: \tilde{D}_0;
tildeD2: =tildeD0/.{xhat->xhat*(1-z)/(1-z-taux)};
tildeDmax: =tildeD0/.{xhat->xhatm}; 

2) Loop+Gluon, pure O(alphas^2): 

tildeDLoopTotal: \tilde{D}_i^{(1),g};

tildeE: \tilde{E}^g;      
tildeF: \tilde{F}^g;
tildeG: \tilde{G}^g;
tildeK: \tilde{K}^g;

tildeEmax: =tildeE/.{xhat->xhatm};
tildeFmax: =tildeF/.{xhat->xhatm};

tildeGs: Derivative of tildeG at taux=0;
tildeKs: Derivative of tildeK at taux=0;

3) Loop+Quark, pure O(alphas^2):

In general, HH means eQ^2, HL eQ*eq, LL eq^2;

tildeQGHH: tilde{G}^{HH};
tildeQGHL: tilde{G}^{HL};
tildeQGLL: tilde{G}^{LL};

tildeQKHH: tilde{K}^{HH};
tildeQKHL: tilde{K}^{HL};
tildeQKLL: tilde{K}^{LL};

tildeQGsHH: Derivative of tildeQGHH at taux=0;
tildeQKsHH: Derivative of tildeQKHH at taux=0;

tildeQGsHL,tildeQGsLL and tildeQKsHL, tildeQKsLL are given in the same way as tildeQGsHH. 
