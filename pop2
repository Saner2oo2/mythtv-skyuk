#!/usr/bin/perl
use v5.14;
use warnings;

until(eof()) {
    my ($id, $chan) = <> =~ /id="([^"]*)".*number="(\d+)"/;
    my ($sign) = <> =~ />(.*)</;
    <>; # Skip </channel>
	<>; # Skip </programme>
		<>; # Skip <programme>
    say qq(UPDATE channel SET channum="$chan",xmltvid="$id" WHERE callsign="$sign");
}
