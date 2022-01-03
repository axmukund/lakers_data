Should use Selenium with Python for webscraping + driving. 

Find each game and look at the Play by Play data

Each possession: 
- Wrapper: <tr _ngcontent-ygw-c213="" class="ng-star-inserted">
- Left side: class="flex flex-1 h-full text-sm text-secondary-800 text-right"
- Right side: class="flex flex-1 h-full text-sm text-secondary-800 text-left"
- Center: class="flex w-8 flex-1" for quarter and class="flex flex-row" for time and class="flex flex-1 justify-end"
    for score part 1 and class="flex flex-1 justify-start" for score part 2
