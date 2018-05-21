# Tutorials
Several short tutorials demonstrating specific objects, features, or patterns commonly used in nelpy.

If you plan to view these notebooks online, we recommend you to use `nbviewer`, which has a much better rendering engine than `github`. You can access this repository at http://nbviewer.jupyter.org/github/nelpy/tutorials .

## Selected tutorials
The tutorials should be followed roughly in order.
  * [**WhirlwindTour**.ipynb](../master/WhirlwindTour.ipynb)—quick overview and simple examples demonstrating the nelpy object model. Start here!
  *  [**EpochArrayTutorial**.ipynb](../master/EpochArrayTutorial.ipynb)—a closer look at the `EpochArrays` object.
  *  [**AnalogSignalArrayTutorial**.ipynb](../master/AnalogSignalArrayTutorial.ipynb)—a closer look at the `AnalogSignalArray` object.
  * more coming soon!

## Coming soon-ish
To add soon:
 - working with contiguous but disjoint epochs (and what to do if your epochs are not disjoint)
 - fixing up a falsely discontinuous object with merge
 - training a hidden Markov model on some animal behavior
 - filtering?
 - position decoding accuracy (internal and external) and cross-validation
 - monkey patching
 - setting domains of objects
 - accessing data with asarray and advanced slicing
 - AnalogSignalArrays vs BinnedSpikeTrainArrays, and moving between them
 - Saving and loading results
 - nelpy FigureContextManager to skip over expensive cells
 - ...
