AndroidExtensions
=================

This project contains some of the custom classes that I've created for Android that may (should?)
have been in the core Android code but for some reason were not.

I've created them to either simplify my life, or fix some of the bugs that are present in the official classes

The ***AndroidExtensions*** project contains:

 * IntegerListPreference - Similar to ListPreference in the core android code, except it allows you to store integer values
   (the default android component crashes, see http://b.android.com/2096)
 * SeekBarPreference - A simple preference that allows you to select an integer value using a seek bar!
 * PreferenceListFragment - For some reason the support library does not have a PreferenceListFragment, so I built one
 * DashboardLayout - presented in the Google I/O app in 2011, it's a custom layout that arranges children in a grid-like manner,
   optimizing for even horizontal and vertical whitespace. Updated with the latest fixes, and changed the namespace to avoid clashes

The ***AndroidExtensions-Sherlock*** project is dependant on ActionBarSherlock and provides the following:

 * SherlockPreferenceListFragment - If you're using ActionBarSherlock and need this, here's a PreferenceListFragment built on top of ActionBarSherlock's ListFragment
