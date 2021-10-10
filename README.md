# Exercise-5.1
GIS 6345 Exercise 5.1 assignment

import time
the_epoch = time.time()

def current_time(since_the_epoch):
	hours = since_the_epoch / 60 / 60
	current_hour = hours - (hours / 24) * 24
	minutes_since = since_the_epoch / 60
	current_minute = minutes_since - (minutes_since / 60) * 60
	second_since = since_the_epoch / 1
	current_second = second_since - (second_since / 60) * 60
	return current_hour, current_minute, current_second

def days_since_the_epoch(epoch):
	days = epoch / 60 / 60 /24
	return days

print(current_time(the_epoch))
(0.0, 0.0, 0.0)
print(days_since_the_epoch(the_epoch))
18910.209080901066

import time
the_epoch = time.time()

def current_time(since_the_epoch):
	hours = since_the_epoch // 60 // 60
	current_hour = hours - (hours // 24) * 24
	minutes_since = since_the_epoch // 60
	current_minute = minutes_since - (minutes_since // 60) * 60
	second_since = since_the_epoch // 1
	current_second = second_since - (second_since // 60) * 60
	return current_hour, current_minute, current_second

def days_since_the_epoch(epoch):
	days = epoch // 60 // 60 /24
	return days
SyntaxError: multiple statements found while compiling a single statement

import time
the_epoch = time.time()

def current_time(since_the_epoch):
	hours = since_the_epoch // 60 // 60
	current_hour = hours - (hours // 24) * 24
	minutes_since = since_the_epoch // 60
	current_minute = minutes_since - (minutes_since // 60) * 60
	second_since = since_the_epoch // 1
	current_second = second_since - (second_since // 60) * 60
	return current_hour, current_minute, current_second

def days_since_the_epoch(epoch):
	days = epoch // 60 // 60 /24
	return days

print(current_time(the_epoch))
(5.0, 6.0, 16.0)
print(days_since_the_epoch(the_epoch))
18910.208333333332
