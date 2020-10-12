# AOdiverData
organized by figure, data in format b64 is raw data from the microsope, see lfdfiles.py on https://www.lfd.uci.edu/~gohlke/#python

data in format .fig can be extracted in matlab.

open('example.fig');
a = get(gca,'Children');
xdata = get(a, 'XData');
ydata = get(a, 'YData');
zdata = get(a, 'ZData');
