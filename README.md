# Gibbs_sampler
An Example of Gibbs Sampler on MatLab

#

% Replicates the textbook results of Chapter 4 on p.73-77.
%
% Application of the Gibbs sampler to simulate: 
% beta|h ~ N(beta1,V1)
% h|beta ~ Gamma(s1^(-2),nu1)

% Note when drawing gamma random numbers: Matlab's definition of the gamma 
% pdf differs from the one of the Koop's textbook.
% Gamma(mu,nu) is Matlab's Gamma(nu/2,2*mu/nu).
