muacrypt: help mail agents manage automated encryption
======================================================

muacrypt provides a command line tool and a Python API to help
mail agents, both user and server-side, integrate and manage automated
e-mail end-to-end encryption with https://autocrypt.org.

Aims and goals
------------------------

- `Fully Autocrypt Level 1 compliant functionality
  <https://github.com/hpk42/muacrypt/milestone/1>`_ for use by mail user agents (MUAs)

- implement `out-of-band verification
  <https://github.com/hpk42/muacrypt/issues/29>`_, with
  `claimchains variants <https://github.com/hpk42/muacrypt/issues/28>`_
  and a `kappa-style architecture <http://milinda.pathirage.org/kappa-architecture.com/>`_.

- `opportunistically encrypted mailing lists with mailman3
  <https://github.com/hpk42/muacrypt/issues/30>`_



Background
----------

The project was so far mainly developed by holger krekel (@hpk42)
with some participation/contributions from @azul, @dkg, @juga0.
Holger's work was and is partially funded by the European Commission
through the `NEXTLEAP <https://nextleap.eu>`_ research project
on decentralized messaging.
The NEXTLEAP project is concerned with
secure identity and e2e-encryption protocols and
aims to contribute to securing Autocrypt against active attacks.

Note that this repository got moved away from the https://github.com/autocrypt
umbrella because that is mainly about the Autocrypt specification efforts itself
while MUA-side implementations happen through different social
arrangements.

.. toctree::
   :hidden:

   install
   cmdline
   diagrams
   api
