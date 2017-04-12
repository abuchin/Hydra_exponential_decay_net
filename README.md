# Hydra_exponential_decay_net

This network is generated based on the assumption that connectivity is random and distance-dependent. The connection probability is determined by the distance on the graph, which might be different in x and y directions. The algorithm generates the matrix based on the known connection probability decay, determined by p(i,j) = p0 * exp [-{(x_i-x_j)^2}/sigma_x -{(y_i-y_j)^2}/sigma_y], where p0, sigma_x and sigma_y are parameters to be estimated from the data.
