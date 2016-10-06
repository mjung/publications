# Certificates... How do they work?

I had the pleasure to present at [MacSysAdmin](http://macsysadmin.se/2016/Home.html) the fourth year in a row. [Tycho](https://twitter.com/tychosjogren) set me the challenge to give an introduction to public key cryptography and public key infrastructures.

### Abstract

We will have a look at certificate based workflows and basic concepts of the cryptography behind it. The goal isn't to make you an expert in the complex domain of certificate-based signatures, encryption, and authentication, but to explore areas this could be useful. 

### Resources

 * [slides (pdf)](https://github.com/mjung/publications/raw/master/2016-10-06_MacSysadmin_Certificates/2016-10-06_MacSysAdmin_Certificates-Marko_Jung.pdf)
 * [video of the presentation (MacSysAdmin.se)](http://docs.macsysadmin.se/2016/video/Day3Session4.mp4)

### Links

 * Overview and introductions:
    * [Apple Developer Library: Cryptography Concepts In Depth](https://developer.apple.com/library/content/documentation/Security/Conceptual/cryptoservices/CryptographyConcepts/CryptographyConcepts.html)
   * [Apple Technical White Paper: 802.1X Authentication](http://training.apple.com/pdf/WP_8021X_Authentication.pdf)
 * [Certificate Transparency](https://www.certificate-transparency.org/)
 
 * PKI Implementations (including some Online Certificate Status Protocol (OSCP) responders):
    * [Microsoft Active Directory Certificate Services](https://technet.microsoft.com/en-us/windowsserver/dd448615.aspx)
    * [EJBCA](https://www.ejbca.org/)
    * [OpenCA PKI Research Labs](https://www.openca.org/)
    * [JAMF Software Server](https://www.jamfsoftware.com/)
    * [XiPKI](https://github.com/xipki/xipki)
 * RFCs for bed time reading:
    * CRL [RFC5280](https://tools.ietf.org/html/rfc5280)
    * OSCP [RFC6960](https://tools.ietf.org/html/rfc6960)
    * Certificate Transparency [RFC6962](https://tools.ietf.org/html/rfc6962)
 * Overview of Simple Certificate Enrolment Protocol [SCEP](www.ietf.org/proceedings/69/slides/pkix-3.pdf)
 * [AFP548: 802.1x EAP-TLS Machine Authentication...](https://www.afp548.com/2012/11/20/802-1x-eaptls-machine-auth-mtlion-adcerts/)
 * Apple
    * [Apple Certificate Authority](https://www.apple.com/certificateauthority/) 
    * [Lists of available trusted root certificates in macOS](https://support.apple.com/en-us/HT202858) *including some info on trust on WoSign CA Free SSL Certificate G2*
 * [GPGTools](https://gpgtools.org/)

### Credits

I would like to thank [Ben](https://github.com/fuzzylogiq/) for his support whilst writing this presentation and Tycho for giving me the opportunity to work on such an interesting topic. 
