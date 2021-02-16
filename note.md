$f_{Z_{OBS}, \mu} (z_{OBS}, \mu^\star)= f_{\mu|Z_{OBS} = z_{OBS}}(\mu^\star) *f_{Z_{OBS}}(z_{OBS})=f_{Z_{OBS}|\mu = \mu^\star}(z_{OBS}) *f_{\mu}(\mu^\star)$


$-2 \ln( f_{\mu|Z_{OBS} = z_{OBS}}(\mu^\star))-2\ln(\frac{1}{(2\pi)^{6/2}\sqrt{det(C_{OBS})}} exp(-\frac{1}{2}(z_{OBS}-\mu)^tC_{OBS}^{-1}(z_{OBS} - \mu)))=-2\ln(\frac{1}{(2\pi)^{6/2}\sqrt{det(C_{OBS})}} exp(-\frac{1}{2}(z_{OBS}-\mu^\star)^tC_{OBS}^{-1}(z_{OBS} - \mu^\star))) - 2ln(\frac{1}{2\sqrt{2\pi}}exp(-\frac{1}{2}(\frac{\mu^\star + 5}{2})^2))$

Après simplification :

$-2 \ln( f_{\mu|Z_{OBS} = z_{OBS}}(\mu^\star)) +(z_{OBS}-\mu\mathbf{1})^tC_{OBS}^{-1}(z_{OBS} - \mu\mathbf{1})=(z_{OBS}-\mu^\star\mathbf{1})^tC_{OBS}^{-1}(z_{OBS} - \mu^\star\mathbf{1})-2\ln(\frac{1}{2\sqrt{2\pi}}) +(\frac{\mu^\star + 5}{2})^2$

Puis :

$-2 \ln( f_{\mu|Z_{OBS} = z_{OBS}}(\mu^\star)) -z_{OBS}^tC_{OBS}^{-1}\mu\mathbf{1} -\mu\mathbf{1}^tC_{OBS}^{-1}z_{OBS} + \mu^2\mathbf{1}^tC_{OBS}^{-1}\mathbf{1} =-z_{OBS}^tC_{OBS}^{-1}\mu^\star\mathbf{1} -\mu^\star\mathbf{1}^tC_{OBS}^{-1}z_{OBS} + (\mu^\star)^2\mathbf{1}^tC_{OBS}^{-1}\mathbf{1}-2\ln(\frac{1}{2\sqrt{2\pi}}) +(\frac{\mu^\star + 5}{2})^2$

$-2 \ln( f_{\mu|Z_{OBS} = z_{OBS}}(\mu^\star)) +5z_{OBS}^tC_{OBS}^{-1}\mathbf{1} +5\mathbf{1}^tC_{OBS}^{-1}z_{OBS} + 25\mathbf{1}^tC_{OBS}^{-1}\mathbf{1} =-z_{OBS}^tC_{OBS}^{-1}\mu^\star\mathbf{1} -\mu^\star\mathbf{1}^tC_{OBS}^{-1}z_{OBS} + (\mu^\star)^2\mathbf{1}^tC_{OBS}^{-1}\mathbf{1}-2\ln(\frac{1}{2\sqrt{2\pi}}) +(\frac{\mu^\star + 5}{2})^2$