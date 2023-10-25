#!/usr/bin/python3
import sys


def check(lst):
    for i in range(len(lst)):
        if (int(lst[i]) % 2 == 0):
            print("{}={}*{}".format(int(lst[i]), int(int(lst[i])/2), "2"))
        elif (int(lst[i]) % 3 == 0):
            print("{}={}*{}".format(int(lst[i]), int(int(lst[i])/3), "3"))
        elif (int(lst[i]) % 5 == 0):
            print("{}={}*{}".format(int(lst[i]), int(int(lst[i])/5), "5"))
        elif (int(lst[i]) % 7 == 0):
            print("{}={}*{}".format(int(lst[i]), int(int(lst[i])/7), "7"))


def main():
    path = sys.argv[1]
    file = open(path, "r")
    file_lst = file.read().splitlines()
    check(file_lst)


if __name__ == "__main__":
    main()
